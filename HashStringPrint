import java.util.Collections;
import java.util.Map;
import java.util.SortedMap;
import java.util.TreeMap;

public class HashStringPrint {

    public static void main(String[] args) {
        String str1 = "Why You Will Probably Pay More for Your Christmas Tree This Year";
        String str2 = str1.toLowerCase();
        SortedMap<Integer, String> map = new TreeMap<>(Collections.reverseOrder());
        String[] strArray = str2.split(" ");
        for (String eachStr : strArray) {
            if (!map.containsValue(eachStr)) {
                map.put(eachStr.length(), eachStr);
            }

        }
        int count = 0;
        for (Map.Entry<Integer, String> entry : map.entrySet()) {
            System.out.println("#" + entry.getValue());
            count++;
            if (count == 3) {
                break;
            }
        }
    }


}

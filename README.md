# salesforcedevclass
Mission 5

public class Mission5 {

    public static void noList(){
        
        List<Integer> input = new List<Integer>{12, 20, 30, 17};
            
            for (Integer n : input){
                If (math.mod(n,3) == 0 && math.mod(n,5) == 0){
                    System.debug('DingDong');
                }
                else if (math.mod(n,3) == 0){
                    System.debug('Ding');                
                }
                else if (math.mod(n,5) == 0){
                    System.debug('Dong');
                }
                else{
                    System.debug(n);
                }
                
            }
    }
}

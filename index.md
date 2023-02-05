# header1?
![image](https://user-images.githubusercontent.com/124476174/216801707-06994a9a-cfbf-49d8-8e4f-cd3b8673e84b.png)
public class ConvertFeet {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // declaring variables
        int feet = 62;
        int yardsLeft; // variable for remaining amount of feet
        int yards;
        
        //begin caculations
        yards = feet / 3;
        yardsLeft = feet % 3;
        
        //printing results
        System.out.println(" Total feet: " + feet
                + "\nyards: " + yards);
    }
    


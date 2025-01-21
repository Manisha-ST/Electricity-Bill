Electricity-Bill

public class ElectricBill {
    public static void main(String args[]) {
        int units = 123;
        int bill = 0;

        if (units > 100) {
            if (units >= 200) {
                if (units > 300) {
                    bill = units * 8;
                } else {
                    bill = units * 6;
                }
            } else {
                bill = units * 5;
            }
        }
        System.out.println("BANGALORE ELECTRICITY LTD, Bangalore");
        System.out.println("Units Consumed : " + units);
        System.out.println("Total Bill : " + bill);
    }
}


OUTPUT:
BANGALORE ELECTRICITY LTD, Bangalore
Units Consumed : 123
Total Bill : 615

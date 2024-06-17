import java.util.Scanner;  // Import lớp Scanner

public class InputExample {
    public static void main(String[] args) {
        // Tạo một đối tượng Scanner để đọc dữ liệu từ System.in
        Scanner scanner = new Scanner(System.in);

        // Đọc một chuỗi ký tự
        System.out.print("Nhập một chuỗi ký tự: ");
        String str = scanner.nextLine();
        System.out.println("Bạn đã nhập chuỗi: " + str);

        // Đọc một số nguyên
        System.out.print("Nhập một số nguyên: ");
        int number = scanner.nextInt();
        System.out.println("Bạn đã nhập số nguyên: " + number);

        // Đọc một số thực
        System.out.print("Nhập một số thực: ");
        double decimal = scanner.nextDouble();
        System.out.println("Bạn đã nhập số thực: " + decimal);

        // Đóng đối tượng Scanner
        scanner.close();
    }
}

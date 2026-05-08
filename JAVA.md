package chapter1;
public class StudentInfo{

    public static void main(String[] args) {
        // TODO: 학생 정보 변수들 선언 및 초기화
        String name = "신형탁";
        int age = 30;
        double height = 176.6;
        char grade = 'X';
        boolean isStudent = false;

        // TODO: 학생 정보 출력
        System.out.println("=== 학생 정보 ===");
        System.out.println("이름: " + name);
        System.out.println("나이: " + age);
        System.out.println("키: " + height + "cm");
        System.out.println("학년: " + grade);
        System.out.println("재학중: " + isStudent);
    }
}

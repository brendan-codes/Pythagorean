● Create a program to calculate the hypotenuse of a right triangle given the values of the two legs

javaFun/Pythagorean.java
```
public class Pythagorean {
    public double calculateHypotenuse(int legA, int legB) {
        // the hypotenuse is the side across from the right angle.
        // calculate the value of c given legA and legB
    }
}
```

javaFun/PythagoreanTest.java
```
public class PythagoreanTest {
    public static void main(String[] args) {
        Pythagorean pythagorean = new Pythagorean();
        double output = pythagorean.calculateHypotenuse(7, 3);
        System.out.println(output); // given 7 and 3, the output should be about ~ 7.61577
    }
}
```

Hints:

● Use a method from the Math class to calculate the hypotenuse of a right triangle given the values of the two legs. HINT: Use the static sqrt method:

```
double four = 4.0;
// calling the sqrt static method of the Math class
double squareRoot = Math.sqrt(four); // 2.0
```


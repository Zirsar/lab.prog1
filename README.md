import java.util.Random;
import static java.lang.Math.*;
public class Main {
    public static void main(String[] args) {
        long[] d;
        d = new long [] {17, 15, 13, 11, 9, 7, 5};
        double[] z;
        z = new double[19];
        for (int i = 0; i < 7; i++) {
            z[i] = (double) (Math.random() * 7 - 4.0);
            
        }
            double[][] f;
            f = new double[7][19];
            double q;
            for (int i = 0; i<7; i++){
            q = (double) d[i];
            for (int j = 0; j < 19; j++){
                if (d[i] == 11){
                    f[i][j] = (asin(cos(pow((pow(exp(q), q) * (0.25 - sin(q))), 3))));}
                if (d [i] == 5 || d[i] == 15 || d[i] == 17){
                    f[i][j] =(cos(tan( 4 / (q - 1))));}
                else {
                    f[i][j] =(cbrt(cbrt(pow(0.25 * (1 - cbrt(q)), 3))));}
            }
            }
            for (int i = 0; i<7; i++){
                for (int j = 0; j<19; j++){
            System.out.printf(" %.2f", f[i][j]);
                   }
                }
                  
          }
}

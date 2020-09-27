# lab.prog1
public class Main {
    public static void main(String[] args) {
        long[] d = {17, 15, 13, 11, 9, 7, 5};
        double[] x = new double[19];
        for (int i = 0; i < 19; i++) {
            x[i] = (double) (Math.random() * 7 - 4.0);
            double[][] f = new double[7][19];
        }
        for (int i = 0; i < 19; i++) {
            x[i] = (double) (Math.random() * 7 - 4.0);
        }
        {
            for (int i = 0; i < 7; i++)
                if (d[i] == 11)
                    f[i][j] = (double)(Math.asin(Math.cos(Math.pow(Math.pow(Math.exp(x), x) * (0.25 - Math.sin(x)), 3))));
                else if (d [i] == 5 && d[i] == 15 && d[i] == 17)
                    f[i][j] = (double)(Math.cos(Math.tan(4 / (x - 1))));
                else
                    f[i][j] =(double)(Math.sbrt(Math.sbrt(Math.pow(0.25 * (1 - Math.sbrt(x)), 3))));
            System.out.printf(" %.2f", f[i][j]);
        }
        System.out.prinln("");
    }
}

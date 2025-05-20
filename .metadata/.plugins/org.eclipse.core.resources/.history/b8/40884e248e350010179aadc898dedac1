package clases;

public class TrianguloRectangulo {
	
	double a;
	double b;
	double c;
	
	/**
	 * 
	 */
    public TrianguloRectangulo() {
        this.a = 1.0;
        this.b = 1.0;
        Hipotenusa();
    }

	/**
	 * Se declaran los siguientes parametros
	 * @param a
	 * @param b
	 * @param c
	 */
	public TrianguloRectangulo(double a , double b, double c) {
		
		this.a= a;
		this.b=b;
		this.c=c;
	}
	
  
    public double getA() {
        return a;
    }
    public double getB() {
        return b;
    }
    
    public double getC() {
        return c;
    }



	/**
	 * Funcion que retorna el area
	 * @return
	 */
	  public double area() {
	        double area = a*b/2;
	        return area;
	    }
	  /**
	   * funcion que retorna el perimetro
	   * @return
	   */
	  public double perimetro() {
	        double d = a+b+c;
	        return d;
	    }

	  /**
	   * funcion que retorna hipotenusa
	   * @return
	   */
	
	private double Hipotenusa() {
        double c = Math.sqrt((a*a) + b*b);
        return c;
   
	}
        @Override
        public String toString() {
            return "TrianguloRectangulo [a=" + a + ", b=" + b + ", c=" + c + "]";
        }


}

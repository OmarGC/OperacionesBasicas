# Clase Operaciones:
Funciones basicas de suma, resta, multiplicacion, divicion. 
 
Uso: 

1.Se crea el objeto:
>Operaciones objeto = new Operaciones(); 

2.Llamada a las funciones:
>objeto.resta(n1, n2);  
>objeto.suma(n1, n2);  
>objeto.mul(n1, n2);  
>objeto.div(n1, n2);  




    /*
     *
     *Autor: OmarGC.
     */
    
    //Variables globales:
    private double n1;
    private double n2;
    private double r;
    
    
    
    /**
     * Metodos Get: Obtener.
     */
    public double getN1() {
        return n1;
    }

    public double getN2() {
        return n2;
    }

    public double getR() {
        return r;
    }
    
    
    
    
    /**
     * Metodos Set: Asignar
     */
    public void setN1(double n1) {
        this.n1 = n1;
    }

    public void setN2(double n2) {
        this.n2 = n2;
    }

    public void setR(double r) {
        this.r = r;
    }
    
    
    /**
     * Metodos Constructor vacio
     */
    public Operaciones() {
    }
    
   
    
    public double suma(double nn1, double nn2){
    double rfinal;
    
    n1 = nn1;
    n2 = nn2;
    
    rfinal = n1 + n2;
    r = rfinal;
    
    
    
    return rfinal;
    
    }
    
    
    public double resta(double nn1, double nn2){
    double rfinal;
    
    n1 = nn1;
    n2 = nn2;
    
    rfinal = n1 - n2;
    r = rfinal;
    
    return rfinal;
    
    }
    
    public double mul(double nn1, double nn2){
    double rfinal;
    
    n1 = nn1;
    n2 = nn2;
    
    rfinal = (n1 * n2);
    r = rfinal;
    
    return rfinal;
    
    }
    
    
    public double div(double nn1, double nn2){
    double rfinal;
    
    n1 = nn1;
    n2 = nn2;
    
    rfinal = n1 / n2;
    r = rfinal;
    
    return rfinal;
    
    }
    
    /**
     * Metodos toString: Encadenar.
     * Indica el formato con el
     * que queremos que se impriman
     * las fechas
     */
    public String toString() {
       return r + "";
    }
    
    
    
    
    

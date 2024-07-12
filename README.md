public class Carro {
    // Atributos (propriedades)
    private String marca;
    private String modelo;
    private int ano;

    // Construtor
    public Carro(String marca, String modelo, int ano) {
        this.marca = marca;
        this.modelo = modelo;
        this.ano = ano;
    }

    // Métodos (comportamentos)
    public void acelerar() {
        System.out.println("O carro está acelerando.");
    }

    public void frear() {
        System.out.println("O carro está freando.");
    }

    // Getters e Setters
    public String getMarca() {
        return marca;
    }

    public void setMarca(String marca) {
        this.marca = marca;
    }

    public String getModelo() {
        return modelo;
    }

    public void setModelo(String modelo) {
        this.modelo = modelo;
    }

    public int getAno() {
        return ano;
    }

    public void setAno(int ano) {
        this.ano = ano;
    }
}

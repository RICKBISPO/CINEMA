class Filme
{
    public String nomedofilme;
    public String sala;
    public String diadasemana;
    public double preco=20;

    public void calcularDesconto()
    {
        if(this.diadasemana.Equals("Quarta-Feira"))
        {
            this.preco = this.preco - (0.5 * this.preco);
        }
        else
        {
            this.preco = 20;
        }
    }

    public String mostrarDados()
    {
        String mensagem="";

        mensagem = ("Nome do Filme:" + this.nomedofilme + "Sala:" + this.sala + "Preço" + this.preco);

        return mensagem;
    }
}

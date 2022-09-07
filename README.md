<php

class Pessoa{

    protected string $Nome;
    private float $Saldo_Banco;

    function_construct(string $Nome, float $Saldo_Banco){
        $this -> nome = $Nome
        $this-> $Saldo_Banco = $Saldo_Banco;
    }

    public function pagarDoritos(float $preço): float{
        return $this ->saldo_banco-$preço;
    }
}

$cliente = New Pessoal('Kraudio' , 22.2);

echo $cliente -> pagarDoritos(11,2)

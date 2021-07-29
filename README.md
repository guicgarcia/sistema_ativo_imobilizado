# sistema_ativo_imobilizado
Sistema desenvolvido com Cakephp E MySqL, para gestão de equipamentos gráficos que precisam ter o seu valor monetário depreciado mês a mês.

Todo mês é atualizado: 
1) O total de meses em que o equipamento depreciou (esteve em uso) 'meses_depreciacao'
2) O valor total que o equipamento depreciou. 'total_valor_depreciacao'
3) O total de meses em que o equipamento ficou guardado no estoque. 'meses_guardado'
   
 Obs: Um equipamento deprecia apenas 36 meses.
 O equipamento começa a depreciar a partir do momento em que é cadastrado um número de nota fiscal.
 O equipamento precisa estar associado a um cliente que não seja o cliente ADM de id = 1.
    

<div align="center">
<img src="https://user-images.githubusercontent.com/29738868/127542547-09926f3a-606f-42c9-80b5-edec88f7df01.png">
</div>

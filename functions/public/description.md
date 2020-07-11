# EasyCourier

A [EasyCourier](https://easycourier.com.br/) é uma plataforma web para criação e gerenciamento de postagem integrado ao WebService Correios. As postagens são criadas no painel da EasyCourier obtendo os dados de pedidos importados da E-Com Plus.
  
Assim que a pré-lista de postagem é fechada no sistema, **o código de rastreio já é informado em sua loja online e o status alterado**.  
  
O rastreio de todas as postagens é atualizado automaticamente de 20 em 20 minutos, quando a postagem é dada pelos Correios como _entregue_ **a EasyCourier atualiza o status do pedido na loja automaticamente**.

## Integração

Após a instalação do app você será redirecionado para cadastro na EasyCourier, basta preencher o cadastro e receberá uma conta associada à sua loja na E-Com Plus. Se você já possui uma conta, instale o app e entre em contato com o suporte da EasyCourier informando seu _Store ID_ da E-Com Plus.

## Processo de geração de postagem

No painel da EasyCourier: 
1. Acesse a aba Postagens > Integração.
2. Serão listados os pedidos com status _aberto_ e status financeiro _pago_;
3. Marca-se o que quer gerar postagem e manda gerar;
4. Depois de gerada a postagem, vá para a aba ao lado Postagens > Criar Postagens onde pode ser editada se preciso;
5. Na aba Postagens > Criar Postagens clique para validar CEPs e depois para fechar a PLP "Pre-lista de postagens";
6. Em seguida poderá imprimir etiquetas e PLP;
7. PLP fechada o sistema envia os códigos para os pedidos e passa o status para _enviado_;
8. As postagens são monitoradas, atualizadas de 20 em 20 minutos e assim que for dada como entregue o sistema passa o status do pedido para _entregue_.

# Computação em Nuvem

Computação em nuvem pode ser classificada em três modelos, sendo:
- Privada;
- Pública;
- Hibrida;

## Computação em Nuvem Privada
São os datacenters on-premises, onde as organizações tem seus próprios datacenters internamente para seu uso exclusivo, neste caso toda a responsabilidade com hardware, sistema, infraestrutura e manutenções são de sua responsabilidade.
O custo entra como CAPEX porque a organização precisa investir em todos os recursos antecipadamente para poder começar a utilizar. Inicialmente o investimento é alto e posteriormente tende a diminuir com o tempo.

## Computação em Nuvem Pública
São os serviços de computação disponibilizados pelos provedores, tendo como exemplo Azure, Oracle, AWS, ETC.. Neste modelo a responsabilidade é compartilhada, a parte de infraestrutura fisica, hardware, energia e internet são de responsabilidade do provedor. O provedor disponibiliza todos os recursos para as organizações/usuários porem utilizar conforme necessidade. A parte de uso, configurações, segurança é de responsabilidade do usuário.
O usuário pode provisionar e desprovisionar os recursos conforme demanda.
O custo entra como OPEX, pois só paga conforme o uso e após o uso. Neste cenário não precisa ter o investimento com toda infraestrutura fisica, manutenção de hardware, refrigeração dentre outros.
Há a opção de fazer a reserva antecida do recurso de forma anual, neste caso entra com custo CAPEX por pagar um valor maior de forma antecipada.

## Computação Híbrida
Este cenário ocorre quando são usado computação em nuvem privada e pública, ou seja, a organização tem parte dos sistemas em seu datacenter e acessa também recursos de provedores públicos como o Azure.

# Azure AI
O Azure disponibiliza diversos modelos de AI, dentre eles estão os da OpenAI. Através do Azure AI Copilot pode ser explorado uma enorme gama destes modelos.
Exemplos praticos apresentados:
- conversão do audio de um video em português para outros idiomas;
- criação de um avatar;
- usado agente para conversar;

Modelos de linguagem pré-processam tokens quebrando o texto em pedaços e tendo um representação númerica, então é aplicado o modelo e com isso se obtem o resultado através da distribuição de probabilidade de se usado a palavra, então é decodificado e temos como saída a linguagem natural.

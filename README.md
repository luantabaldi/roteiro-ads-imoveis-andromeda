# Roteiro de ads para imoveis (padrao Andromeda)

Skill do Claude que ajuda videomakers e gestores de trafego a montar roteiros de video para anuncios de imoveis no padrao Andromeda da Meta: cada roteiro combina Persona, Angulo e Oferta, e cada lote traz conceitos distintos para gerar Entity IDs separados.

## O que a skill faz

1. Coleta os dados do imovel (tipo, endereco, valor, condicoes, diferenciais).
2. Faz ate 3 perguntas rapidas (quantidade de roteiros, persona prioritaria, formato).
3. Monta a matriz de conceitos, variando pelo menos duas das tres variaveis entre os roteiros.
4. Escreve cada roteiro com gancho, corpo, oferta, CTA e duracao estimada.
5. Revisa os ganchos contra a politica de atributos pessoais da Meta antes de entregar.

## Como instalar

1. Baixe este repositorio e compacte a pasta `roteiro-ads-imoveis-andromeda` em um arquivo ZIP. O nome da pasta precisa ficar exatamente assim.
2. No Claude, va em **Customize > Skills**.
3. Clique em **+**, depois **+ Create skill** e **Upload a skill**, e envie o ZIP.
4. Ative a skill na lista.

## Como usar

Abra uma conversa no Claude e peca, por exemplo:

> Monte 5 roteiros de ads para este imovel: apartamento 3 quartos, 1 suite, 2 vagas, Alameda Princesa Izabel 1240, R$ 1.200.000.

A skill pergunta o que faltar e entrega a tabela de conceitos mais os roteiros numerados.

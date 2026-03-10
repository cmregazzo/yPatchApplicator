# yPatchApplicator - Aplicador de Patches
O yPatchApplicator é um facilitador de aplicação de Patches, no qual deverá ser executado diretamente no Computador/Servidor onde está configurado o Servidor de Aplicação. Atualmente o yPatchApplicator só funciona em Sistemas Operacionais Windows.

## Funcionalidades

- Área Seleção de Patches - Essa área, é designada a seleção dos Patches que serão aplicados ao Profile selecionado. Após seleção dos Patches, é possível verificar o Status de aplicação dos mesmos, Nome dos Patches, além do seu Release (essa informação só é preenchida quando o release está contido no nome do Patch). Nessa área também, é possível verificar o Total de Patches selecionados para aplicação.

- Área de Aplicação de Patches:	
	- Criação/Seleção de Profiles - Crie vários perfis de aplicação de Patches (ícone de engrenagem) de acordo com a sua necessidade. Com isso, é possível configurar perfis independentes, conforme versão, instalação, e/ou ambientes, baseados no Servidor de Aplicação.
	- Console do Servidor de Aplicação - Nessa área é possível acompanhar as aplicações dos Patches, além da desfragmentação do Repositório de Objetos, quando tal opção for marcada.
	- Status: Nessa área é exibida a quantidade de Patches aplicados com sucesso e erro, barra de progresso demonstrando o andamento das aplicações de Patches e/ou desfragmentação do Repositório de Objetos, além de demonstrar a quantidade total de Patches a aplicar, além da quantidade de Patches já aplicados.
	- Botão Aplicar Patches - Esse é o botão responsável por fazer aplicação dos Patches selecionados, na área de Seleção de Patches, além de executar as funcionalidades setadas a área de Opções. Conforme os Patches vão sendo aplicados é exibida uma linha no ListView de Patches, demonstrando qual o Patch que está sendo aplicado no momento.

- Área de Opções: 
	- Aplicar Patches Antigos - Marcando essa opção, caso algum Patch tenha fontes antigos, o mesmo será aplicado no Repositório de Objetos.
	- Limpar o Console a cada Aplicação de Patch - Com essa funcionalidade ativa, ao aplicar mais de um Patch, a área demarcada no software como "Console", é automaticamente "limpa", exibindo apenas, a aplicação do Patch atual.
	- Validar Patches Previamente - Essa funcionalidade será implementada em versões futuras.
	- Desfragmentar RPO ao Finalizar - Marcando essa opção, ao finalizar a aplicação de Patches, o yPatchApplicator irá automaticamente Desfragmentar o Repositório de Objetos, eliminando fragmentações internas, otimizando sua estrutura, removendo espaços vazios, diminuindo seu tamanho e melhorando sua performance de leitura.

## Guia Rápido

A utilização do yPatchApplicator é bem fácil e intuitiva. Segue os passos para configuração e aplicação dos Patches:

- Crie um Profile (perfil) de Ambiente para aplicação dos Patches. Para tanto, clique no Botão de "Engrenagem", localizado na Área de Aplicação de Patches. Será aberta uma nova tela, na qual deverá ser preenchidas as informações do Path do Servidor de Aplicação e seu respectivo arquivo de configuração (.ini), além de selecionar o Ambiente do Servidor e o Release do mesmo. Nessa tela pode-se criar quantos Profiles for necessário.

- Selecione os Patches que serão utilizados na atualização do ambiente, clicando no botão "Selecionar Patches".

- Em seguida selecione as opções desejadas, e clique no Botão "Aplicar Patches", para iniciar a atualização do Ambiente selecionado no Profile.
	
Pode-se acompanhar aplicação online dos Patches, através do "Console do Servidor de Aplicação".

Em Status, é possível verificar a quantidade de Patches aplicados com sucesso e com erro (caso ocorra algum problema). Já em "Aplicando Patch", é possível verificar quantos Patches já foram aplicados e quantos faltam a ser aplicados. Além disso, temos a progess bar, na qual demonstra o andamento do processo de atualização do Ambiente.

Na Área de Seleção de Patches, através do ListView, é possível verificar o Status de aplicação dos Patches (sucesso ou erro), além de ter uma linha dinâmica, a qual demonstra o Patch que está sendo aplicado.

## Suporte/Sugestões de Melhorias e/ou Funcionalidades

Caso encontre algum problema no yPatchApplicator, ou tenha uma Sugestão de Melhoria e/ou Funcionalidade, pedimos, por favor, que abra uma Issue conosco aqui mesmo.

O yPatchApplicator é um software "vivo", com isso toda opinião, report de erros, sugestão de melhoria/funcionalidades, são de extrema importância para fazer com que o yPatchApplicator, seja sempre um software de qualidade e que facilite cada vez mais a o dia a dia dos Analistas, portanto para termos um canal de comunicação sempre disponível, sempre que achar necessário, pode-se abrir uma [Issue](https://github.com/cmregazzo/yPatchApplicator/issues) aqui mesmo no repositório.

Os erros corrigidos e as melhorias implementadas pela equipe do yPatchApplicator, também serão controladas via Issues e descritas nos Release.

## Código-Fonte

Este repositório não contém o código-fonte do software, que a princípio, permanecerá privado. No entanto, o projeto será mantido aqui no GitHub para:

- Acesso ao histórico de Release Notes;

- Consulta das funcionalidades;

- Registro e acompanhamento de dúvidas, melhorias, problemas, etc., através das Issues.

## Mantenedor

Cristian Regazzo - cmregazzo@gmail.com

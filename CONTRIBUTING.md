# Contribuindo

Ao contribuir para este repositório, por favor, primeiro discuta a alteração que deseja fazer via issue, e-mail ou qualquer outro método com os responsáveis pelo repositório antes de realizar a alteração.

Por favor, observe que temos um código de conduta. Siga-o em todas as suas interações relacionadas ao projeto.

## Relatando Bugs

Esta seção orienta sobre como enviar um relatório de bug para o DNX. Seguir essas diretrizes ajuda os mantenedores e a comunidade a entenderem seu relatório, reproduzirem o comportamento e encontrarem relatórios relacionados.

Antes de criar relatórios de bugs, verifique esta lista, pois talvez você não precise criar um. Ao criar um relatório de bug, por favor, [inclua o máximo de detalhes possível](#como-enviar-um-bom-relatorio-de-bug). Preencha [o modelo obrigatório, pois as informações solicitadas ajudam a resolver problemas mais rapidamente].

### Como Enviar Um (Bom) Relatório de Bug?

Os bugs são rastreados como [issues do GitHub](https://guides.github.com/features/issues/). Crie uma issue no repositório e forneça as seguintes informações ao preencher o modelo:

Explique o problema e inclua detalhes adicionais para ajudar os mantenedores a reproduzir o problema:

- **Use um título claro e descritivo** para identificar o problema.
- **Descreva os passos exatos para reproduzir o problema** com o máximo de detalhes possível. Por exemplo, explique como você iniciou o módulo, como o comando utilizado no terminal.
- **Forneça exemplos específicos para demonstrar os passos**. Inclua links para arquivos ou projetos no GitHub, ou trechos que possam ser copiados e colados. Caso forneça trechos na issue, use [blocos de código Markdown](https://docs.github.com/pt/github/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks).
- **Descreva o comportamento observado após seguir os passos** e destaque qual é exatamente o problema com esse comportamento.
- **Se o problema não foi causado por uma ação específica**, descreva o que você estava fazendo antes que o problema ocorresse e compartilhe mais informações usando as diretrizes abaixo.

Forneça mais contexto respondendo às perguntas:

- **O problema começou a ocorrer recentemente** (ex.: após atualizar para uma nova versão do Terraform) ou sempre foi um problema?
- Se começou recentemente, **você consegue reproduzir o problema em uma versão anterior do Terraform?** Qual é a versão mais recente em que o problema não ocorre? Você pode baixar versões antigas do Terraform na [página de releases](https://github.com/hashicorp/terraform/releases).
- **Você consegue reproduzir o problema de forma confiável?** Caso não, forneça detalhes sobre a frequência e as condições em que o problema ocorre.
- Se o problema está relacionado a arquivos, **ele ocorre com todos os arquivos e projetos ou apenas alguns?** Ele ocorre apenas com arquivos locais ou remotos, de um tipo específico, com arquivos grandes ou de linhas muito longas? Existe algo especial sobre os arquivos usados?

## Sugerindo Melhorias

Esta seção orienta sobre como enviar sugestões de melhorias para os módulos DNX, incluindo novas funcionalidades ou melhorias em funcionalidades existentes. Seguir essas diretrizes ajuda os mantenedores e a comunidade a entenderem sua sugestão e encontrarem sugestões relacionadas.

Antes de criar sugestões, verifique as issues, pois você pode descobrir que não é necessário criar uma nova. Ao criar uma sugestão, inclua o máximo de detalhes possível. Preencha o modelo, incluindo os passos que você imagina que tomaria se o recurso solicitado já existisse.

### Como Enviar Uma Boa Sugestão de Melhoria?

As sugestões de melhorias são rastreadas como [issues do GitHub](https://guides.github.com/features/issues/). Crie uma issue no repositório e forneça as seguintes informações:

- **Use um título claro e descritivo** para identificar a sugestão.
- **Forneça uma descrição passo a passo da melhoria sugerida** com o máximo de detalhes possível.
- **Forneça exemplos específicos para demonstrar os passos**. Inclua trechos que possam ser copiados e colados, como [blocos de código Markdown](https://help.github.com/articles/markdown-basics/#multiple-lines).
- **Descreva o comportamento atual** e **explique o comportamento esperado** e por quê.
- **Inclua capturas de tela ou GIFs animados** para demonstrar os passos ou apontar partes do código relacionadas. Você pode usar [esta ferramenta](https://www.cockos.com/licecap/) no macOS e Windows, ou [esta ferramenta](https://gitlab.gnome.org/Archive/byzanz) no Linux.
- **Explique por que essa melhoria seria útil** para a maioria dos usuários do Terraform e por que não deve ser implementada como um pacote comunitário.
- **Especifique a versão do Terraform que você está usando.** Execute `terraform -v` no terminal para obter a versão exata.
- **Especifique o nome e a versão do sistema operacional que você está usando.**

## Processo de Pull Request

O processo descrito aqui tem vários objetivos:

- Resolver problemas importantes para os usuários.

1. Atualize o README.md com detalhes das mudanças na interface, incluindo novas variáveis de ambiente, portas expostas, locais úteis de arquivos e parâmetros do contêiner.
2. Aumente os números de versão nos arquivos de exemplo e no README.md para a nova versão que este Pull Request representaria. O esquema de versionamento usado é o [SemVer](http://semver.org/).
3. Você pode fazer o merge do Pull Request após a aprovação de dois outros desenvolvedores ou, caso não tenha permissão, pode solicitar a um revisor para fazer isso por você.
4. Siga todas as instruções no [modelo](./.github/pull_request_template.md).
5. Siga os [guias de estilo](https://docs.dnx.one/docs/style-guide/terraform-style-guide.html).
6. Após enviar seu Pull Request, verifique se todos os [status checks](https://help.github.com/articles/about-status-checks/) estão passando.

### Sua Primeira Contribuição de Código

Não sabe por onde começar? Confira as issues `beginner` e `help-wanted`:

- `beginner` - issues que requerem apenas algumas linhas de código e um ou dois testes.
- `help-wanted` - issues um pouco mais complexas que as de `beginner`.

Ambas as listas são ordenadas pelo número total de comentários. Embora não seja perfeito, o número de comentários é um bom indicador do impacto de uma alteração.

# ✨ Como Contribuir para o Guia Linux ✨

Agradeço o seu interesse em contribuir para o **guiaLinux**! Sua ajuda é muito valiosa para manter este repositório atualizado, preciso e cada vez mais completo.

Este documento detalha o processo para sugerir melhorias, correções ou a adição de novos comandos ao guia.

---

## 💡 Maneiras de Contribuir

Existem várias formas de contribuir para este guia:

1.  **Adicionar Novos Comandos:** Sugerir comandos Linux úteis que ainda não estão listados no `README.md`.
2.  **Melhorar as Descrições:** Tornar as descrições dos comandos existentes mais claras, objetivas ou precisas.
3.  **Corrigir Erros:** Reportar e corrigir erros de digitação (typos), sintaxe, ou informações incorretas.
4.  **Melhorar a Formatação:** Ajudar a manter a formatação Markdown consistente e visualmente agradável.

---

## 🚀 Fluxo de Contribuição (Passo a Passo)

Siga os passos abaixo para submeter sua contribuição:

### 1. Faça um Fork do Repositório

Faça um *fork* do repositório `https://github.com/menezeslivia/guiaLinux.git` para sua conta do GitHub.

### 2. Clone o Repositório

Clone o repositório **que você criou o fork** para sua máquina local.

```bash
git clone [https://github.com/SEU_USUARIO/guiaLinux.git](https://github.com/SEU_USUARIO/guiaLinux.git)
cd guiaLinux
````

### 3\. Crie um Ramo (Branch) para a Sua Mudança

É uma boa prática criar um ramo específico para cada contribuição. Use um nome claro que descreva sua mudança (ex: `adicionar-comando-sed`, `correcao-descricao-ls`).

```bash
git checkout -b nome-do-seu-ramo
```

### 4\. Faça Suas Alterações

Edite o arquivo **`README.md`** ou adicione qualquer outro arquivo necessário.

#### Padrão de Comandos (ao adicionar um novo):

  * **Tabela de Comandos:** Certifique-se de que o novo comando está sendo adicionado à seção temática correta (Navegação, Rede, etc.) usando a sintaxe de tabela Markdown.
  * **Formato:** Use `código` para o comando e forneça uma descrição concisa e clara. Adicionar um emoji opcional (como os que já existem) é bem-vindo, mas não obrigatório.

| Comando | Descrição |
|---------|-----------|
| `novo-comando` | Descrição clara e concisa do comando 🌟 |

### 5\. Commit e Push

Após salvar suas alterações:

```bash
# Adiciona as alterações para o "stage"
git add . 

# Cria o commit com uma mensagem descritiva
git commit -m "feat: Adiciona comando 'grep' e melhora descrição de 'find'"

# Envia as alterações para o seu fork no GitHub
git push origin nome-do-seu-ramo
```

### 6\. Abra um Pull Request (PR)

Vá para a página do seu repositório bifurcado no GitHub e você verá um botão para **"Compare & pull request"**.

  * **Título do PR:** Deve ser direto e resumir a mudança (ex: "Adiciona seção de Variáveis de Ambiente").
  * **Descrição do PR:** Explique a motivação da sua mudança e o que foi alterado.

Sua contribuição será revisada e, se aprovada, será mesclada ao repositório principal\!

-----

## 💬 Dúvidas ou Sugestões

Se você tiver dúvidas sobre o projeto ou não souber como implementar uma melhoria, sinta-se à vontade para **abrir uma Issue** (Relatório de Problemas) no repositório.

Agradeço novamente por ajudar a construir um Guia Linux cada vez melhor\!

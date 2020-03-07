# Template-do-Latex-para-TCC
Template do Latex para Trabalho de Conclusão de Curso na UFVJM, respeitando as normas da biblioteca referente ao mesmo.

# Algumas instruções de uso


# Adicionando figura:

\begin{figure}[htb]
 \centering
 \caption{Título}
 \includegraphics[width=0.7\textwidth]{figuras/figura}
 \label{apelido}
 \fonte{\apud{citação-indireta}{citação-direta}.}
\end{figure}

# Adicionando tabela:

\begin{table}[h]
\centering
\scalefont{1.1}
\caption{Título}
\vspace{0.5cm}
\begin{tabular}{l|c|c|c}
\textbf{coluna 0} & \textbf{\textit{coluna 1}} & \textbf{\textit{coluna 2}} & \textbf{\textit{coluna 3}} \\ % Note a separação de col. e a quebra de linhas
\hline                               % para uma linha horizontal
 0 & 1 & 2 & 3 \\ %linha
Facilidade de configurar um site simples & 3 & 3 & 3 \\
Curva de aprendizado para configurar um site complexo & 2 & 1 & 3 \\
Facilidade edição de conteúdo & 3 & 3 & 3 \\
Facilidade de gerenciar um site & 2 & 2 & 3 \\
Flexibilidade estrutural & 3 & 3 & 2 \\
Flexibilidade gráfica & 3 & 3 & 3 \\
Flexibilidade de suporte móvel & 3 & 3 & 3 \\
Integração com dados constituintes & 2 & 2 & 1 \\
Funções de usuário e fluxo de trabalho & 2 & 3 & 2 \\
Comunidade/Funcionalidade na Web 2.0 & 3 & 2 & 3 \\
Acessibilidade & 3 & 3 & 2 \\
Otimização para mecanismos de pesquisa & 2 & 3 & 2 \\
Estendendo além da funcionalidade existente & 3 & 3 & 3 \\
Apoio e força da comunidade & 3 & 3 & 3 \\
\hline   
\end{tabular}
\fonte{\citeonline{citação-indireta}. Adaptado.}
\label{apelido}
\end{table}

# Citação superior a 3 linhas:

\begin{citacao}
Indústrias como fabricação, viagens e hospitalidade, bancos, educação e governo estão habilitados na web para melhorar e aprimorar suas operações. O comércio eletrônico expandiu-se rapidamente, atravessando fronteiras nacionais. Até os sistemas tradicionais de informações e bancos de dados herdados migraram para a Web. \cite[p. 1]{citação}.
\end{citacao}

# Adicionando quadro:

\begin{quadro}[h]
\centering
\scalefont{0.8}
\caption{Título}
\vspace{0.5cm}
\begin{tabular}{c|c}
\textbf{Características} & \textbf{Gerenciamento Tradicional} \\ % Note a separação de col. e a quebra de linhas
\hline                               % para uma linha horizontal
linha 0 \\
linha 1 \\
linha 2 \\
linha 3 \\
\hline
\end{tabular}
\fonte{\citeonline{citação}. Adaptado.}
\label{apelido}
\end{quadro}

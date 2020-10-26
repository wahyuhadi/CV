### MY personal CV
- build with lualatex
  ```sh
  lualatex cv_13.tex
  ```

- If u will add referee
```sh
%----------------------------------------------------------------------------------------
%	REFEREE SECTION
%----------------------------------------------------------------------------------------

\section{Referees}

\parbox{0.5\textwidth}{ % First block
\begin{tabbing}
\hspace{2.75cm} \= \hspace{4cm} \= \kill % Spacing within the block
{\bf Name} \> Bill Lumbergh \\ % Referee name
{\bf Company} \> Initech Inc. \\ % Referee company
{\bf Position} \> Vice President \\ % Referee job title 
{\bf Contact} \> \href{mailto:bill@initech.com}{bill@initech.com} % Referee contact information
\end{tabbing}}


\hfill % Horizontal space between the two blocks
\parbox{0.5\textwidth}{ % Second block


\begin{tabbing}
\hspace{2.75cm} \= \hspace{4cm} \= \kill % Spacing within the block
{\bf Name} \> Michael "Big Mike" Tucker\\ % Referee name
{\bf Company} \> Burbank Buy More \\ % Referee company
{\bf Position} \> Store Manager \\ % Referee job title 
{\bf Contact} \> \href{mailto:mike@buymore.com}{mike@buymore.com} % Referee contact information
\end{tabbing}}

%----------------------------------------------------------------------------------------
```

# Journal paper
This is the paper submitted to the journal.
Once you have submitted, make sure to tag the repo with `R0`.

## Revisions
Use the code below for highlighting journal revision changes using the `\hl{}` commands.

```
\usepackage{soul}
\definecolor{bananamania}{rgb}{0.98, 0.91, 0.71}
\sethlcolor{bananamania}
% These commands make the highlights work on the refs
\soulregister\cite7
\soulregister\citep7
\soulregister\citet7
\soulregister\ref7
\soulregister\eqnref7
% If you need more than one color, use this:
\definecolor{rev1}{HTML}{FF999A} % red
\definecolor{rev2}{HTML}{F3F298} % yellow
\definecolor{rev3}{HTML}{B2E0AE} % green
\definecolor{other}{HTML}{C8C7FF} % blue
\DeclareRobustCommand{\hlone}[1]{{\sethlcolor{rev1}\hl{#1}}}
\DeclareRobustCommand{\hltwo}[1]{{\sethlcolor{rev2}\hl{#1}}}
\DeclareRobustCommand{\hlthree}[1]{{\sethlcolor{rev3}\hl{#1}}}
\DeclareRobustCommand{\hlo}[1]{{\sethlcolor{other}\hl{#1}}}
\DeclareRobustCommand{\hlone}[1]{{\sethlcolor{white}\hl{#1}}}
\DeclareRobustCommand{\hltwo}[1]{{\sethlcolor{white}\hl{#1}}}
\DeclareRobustCommand{\hlthree}[1]{{\sethlcolor{white}\hl{#1}}}
\DeclareRobustCommand{\hlo}[1]{{\sethlcolor{white}\hl{#1}}}
```

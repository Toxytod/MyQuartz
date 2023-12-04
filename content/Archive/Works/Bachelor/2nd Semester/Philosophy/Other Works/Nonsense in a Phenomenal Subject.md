#### Reference to Former Writings
I exposed in [[The Frequency of Telling Stories]] what is a denotation of "I" in different contexts, though, what remained constant in that essay, was that I regarded the "I" as being external. I always gave examples where "I" was said by an outer subject or it was me but at a past time or referring the the future. Ultimately I have treated the proper, present "I" and described it in "5.3 The Actual World":
	I define the actual world as being the world in which there is nothing counterfactual and, as I have shown before, every proposition containing qualia implies that I am someone that I am not. Therefore the actual world would be the world in which I’m able to denote precisely the things as I perceive but, as shown, I can’t communicate them to anyone or even myself at a later time. So if you consider the limit of two subjects to their being the same (two very similar people or the same subject after an infinitesimal fraction of time), they would be able to communicate their actual world with qualia. On the other hand the world of ideas, because of its lack of indexicals, would also be a partial description of the actual world.
Here we see that I regarded the actual world as being something I cannot comunicate. I still agree with that idea but I want to give a different argument in order to get to a similar conclusion, this should show how obvious it already was that, in the context I built, there was no space for a definable present proper "I".
#### Definability
Similarly as I have seen in [[Model Theory (Lecture)]], in order for something to be definable there should be a proposition that satisfies it and nothing else, a remarkable example of the concept is the following: Consider the language of ordered groups $\mathcal{L}_{og}:=\langle +, >, 0 \rangle$ and the ordered group $(\mathbb{Q}, +, >)$ . In this case we have no way to define $1$, since there is no $\phi \in \mathcal{L}_{og}$  s.t. $\phi(1)$ is true and false for any other variable.
I want to use here a similar concept of definability, which would then become exactly the same if I would be able to write my theory formally. In particular I should notice that there some sort of propositions that have a free variable and are therefore of the desired kind, but that are true for any inserted variable. For the former example we may for example take $\psi(y):= \exists_y y>x$ , we notice that whatever we insert in the free variable $y$ it would always be true. Though I see convenience in statin that, a proposition $\phi(x)$ defines something, only if there is something that it is not defining, therefore $\psi(x)$ would not be a defining proposition. It would be a defining proposition, e.g., in the ordering $(\mathbb{Z}/(5), >)$ where $\lnot \psi(4)$  holds.
#### The Subject
When asking whether the subject is definable we must first well specify the language we are speaking in. There may well be different ways to define subjects if we are talking a more externalist language or simply referring to others, though, if we consider the present self, in a completely internalist language, like the one I'm trying to write in \[unpublished writings\], then one immediately notice that what we mean by subject is including everything that is present in our domain of discourse. Therefore we will find no defining proposition fo subject, since it would hold for any element of our discourse.
#### Application to Descartes
I regard the Cartesian _cogito ergo sum_ as: from the presence (in my sensations) of any thoughtful activity, it must follow that there is a subject who produced it. And yet, here, i just gave a model where the former sentence can't turn out to be true, since subject, as shown, is not definable. Two objections come first to my mind: (i) I am not referring to the same subject Descartes is meaning and (ii) the Cartesian claim is then not true, which doesn't strictly mean to be false. For (i) I need first to state the disclaimer that I have no historical pretence and secondly that I suppose that Descartes wants to denote with subject, either the totality of the res cogitans, for which my argument holds, or the author of such a totality, which would not be part of the domain of discourse and therefore not definable either. For (ii) I would first underline that what Descartes needed is something to be true in any model of our perception, s.t. no sceptical scenario could still both explain our sensations and not satisfy. My scenario though explains all our sensations, by just assuming the presence of such phenomena, and doesn't satisfy the existence of a subject, therefore I would be enough of a sceptical scenario to falsify the Cartesian claim.
##### $\LaTeX$ file
![[Nonsense_in_a_Phenomenal_Subject.pdf]]
##### $\LaTeX$ code

```LaTeX
\documentclass{article}
\usepackage{amsthm}
\usepackage{csquotes}
\usepackage{amsfonts}
\usepackage{amsmath}
\usepackage{setspace}
\usepackage[greek,english]{babel}
\usepackage[letterpaper,top=2cm,bottom=2cm,left=3cm,right=3cm,marginparwidth=1.75cm]{geometry}
\usepackage{graphicx}
\usepackage[colorlinks=true, allcolors=blue]{hyperref}
\title{Nonsense in a Phenomenal Subject}
\author{Simone Testino}
\date{July 2023}

\begin{document}

\maketitle
\begin{abstract}
    In this short writing I try to give a counterexample to the Cartesian cogito ergo sum, by showing that there are models where there are thoughts and no subject producing it. In such models talking about subjects becomes nonsense since, as I will show, it won't be a definable word. The attempt of the writing is not to give a conclusive explanation of why things appear in the way they appear, I will rather do the opposite: I will bring \emph{one of the many} scenarios one could give that explain our perception; the particular feature of my model will be that thinking will require no subject and will therefore deny the Cartesian \emph{cogito ergo sum}.
\end{abstract}

\subsection*{I. Reference to Former Writings}
I exposed in \enquote{The Frequency of Telling Stories} what is a denotation of \enquote{I} in different contexts, though, what remained constant in that essay, was that I regarded the \enquote{I} as being external. I always gave examples where \enquote{I} was said by an outer subject or by me in the past or referring to the future. Ultimately I have treated the proper, present \enquote{I} and described it in \enquote{5.3 The Actual World}:

\begin{quote}
I define the actual world as being the world in which there is nothing counterfactual and, as I have shown before, every proposition containing qualia implies that I am someone that I am not. Therefore the actual world would be the world in which I’m able to denote precisely the things as I perceive them but, as shown, I can’t communicate those to anyone or even myself at a later time. So if you consider the limit of two subjects to their being the same (two very similar people or the same subject after an infinitesimal fraction of time), they would be able to communicate their actual world with qualia [and therefore communicating the \enquote{I} as I mean it in this writing]. On the other hand the world of ideas, because of its lack of indexicals, would also be a partial description of the actual world.
\end{quote}

Here we see that I regarded the actual world as being something I cannot communicate. I still agree with that idea but I want to give a different argument in order to get to a similar conclusion. This should show how obvious it already was that, in the fully internalist context I built, there was no space for a definable present \enquote{I}.

\subsection*{II. Definability}
Similarly as I have learnt in the Model Theory course, in order for something to be definable there should be a proposition that satisfies it and nothing else, a remarkable example of the concept is the following: Consider the language of ordered groups $\mathcal{L}_{og}:=\langle +, >, 0 \rangle$ and the ordered groups $(\mathbb{Q}, +, >)$. In this case we have no way to define $1$, since there is no $\phi \in \mathcal{L}_{og}$  s.t. $\phi(1)$ is true and false for any other variable.
I want to use here a similar concept of definability, which would then become exactly the same if I would be able to write my theory formally. In particular I should notice that there are some sort of propositions that have a free variable and are therefore of the desired kind, but that are true for any inserted variable. For the former example we may for example take $\psi(y):= \exists_y y>x$ , we notice that whatever we insert in the free variable $y$ it will always be true. Though I see convenience in stating that, a proposition $\phi(x)$ defines something, only if there is something that it is not defining, therefore $\psi(x)$ would not be a defining proposition. It would be a defining proposition, e.g., in the ordering $(\mathbb{Z}/(5), >)$ where $\lnot \psi(4)$  holds.

\subsection*{III. The Subject}
When asking whether the subject is definable we must first well specify the language we are speaking in. There may well be different ways to define subjects if we are talking a more externalist language or simply referring to others, though, if we consider the present self in a completely internalist language, then one immediately notices that what we mean by subject is including everything that is present in our domain of discourse. Therefore we will find no defining proposition of the subject, since it would hold for any element of our discourse.

\subsubsection*{III.I. Collections of Phenomena}
One might argue that constructing a defining formula is well possible, since it would be the one satisfied only by the \emph{set} of all phenomena and unsatisfied by all other sets that don't contain the totality of the phenomena. To argue against this attempt I underline the fact that one can, as want to do for this model, consider collections a distinct element. Now, the former proposal for a defining formula would look like this $\phi(x):= \forall_y y \subseteq x$. Clearly what we need here is a partial ordering of these collections like "$\subseteq$". I claim that there are models that still coherently explain our perception that would have not such an ordering, for instance, consider the processed image I have of an object, say, my keyboard. I could clearly say, that there are some other processed images that take part to the image I am right now having of keyboard: one might simply mention its colour, or the material or the sound it is making. These are all phenomena that put together \emph{compose} the final object I am now looking at. Two things to notice here: first it should now be clear what I mean when claiming that the collection is a distinct object from the phenomena which is \emph{composing} it. Is \emph{composing} the right word? We could say that $1, 2$ together compose $\{1, 2\}$ but I doubt that grey, metal and a clicky sound compose my keyboard. The pretence of having such an ordering between composite and simpler phenomena is something that clearly brings a few difficulties that one may simply prefer not to solve. Remember here the methodological maxim, I am not pretending to explain how things are but just giving \emph{one of the many} scenarios that explain our perception.

\subsection*{IV. Application to Descartes}
I regard the Cartesian \emph{cogito ergo sum} as: from the presence (in my sensations) of any thoughtful activity, it must follow that there is a subject who produced it. And yet, here, I just gave a model where the former sentence can't turn out to be true, since the subject, as shown, is not definable. Two objections came first to my mind: (i) I am not referring to the same subject Descartes is meaning and (ii) the Cartesian claim is then not true in the shown model, which doesn't strictly mean that it is false. For (i) I need first to state the disclaimer that I have no historical pretence and secondly that I suppose that Descartes wants to denote with subject, either the totality of the res cogitans, for which my argument holds, or the author of such a totality, which would not be part of the domain of discourse and therefore not definable either. For (ii) I would first underline that what Descartes needed is something to be true in any model of our perception, s.t. no sceptical scenario could still arise: both justifying our sensations and not satisfy his claim. Though my scenario both explains all our sensations, by just assuming the presence of such phenomena, and does not satisfy the existence of a subject, therefore I am convinced that it is a sceptical scenario able to falsify the Cartesian claim.

\end{document}
```
### Answer:
I sent the former LaTeX to [[V. Wagner]] asking for:
	In der letzten Hausaufgabe habe ich angefangen, eine Idee zu entwickeln, die ein Versuch ist, ein skeptisches Szenario zu finden gegen das Cogito Argument. Da ich in der Hausaufgabe nicht die ganze Idee darstellen könnte, schicke ich Ihnen eine bessere Erklärung davon. Die Fragen sind immer noch (i) falls Sie ähnliche Ideen in der Literatur kennen und (ii) falls sie glauben, dass das Argument stimmt (und was wahrscheinlich unterschiedlich ist, (iii) falls Sie glauben dass Descartes damit einverstanden wäre)
As answer i got:
The professor answered me directly during the lecture without reading the text which I explained briefly during the class. There have been some very useless points like "what about time? how do you handle it in solipsim?" or some other whcih all clearly used an externalist language. One objection has been interesting though namely the fact that you could simply have a proposition running on set of impression that is true only for the set containing all of them and false otherwise. Talking with Makki, though, I found one simple answer to that: when I am referring to a composite of ideas, I am actually referring to a new object and not a collection of objects. I regard therefore sets as being objects, one can imagine it by considering that the image of a table is a composite image since it entails its colour, material, impression of its partial parts, and so on. Though the idea of the table or its processed impression clearly is one element of the whole set and not a subset of it. Therefore the variable we are running on are only elements and not subsets of the whole set, and therefore such a proposition defining the "I" cannot be stated.
The new LaTeX should give a sufficiently good explanation of why I regard this still as being a good argument.
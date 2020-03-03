 <script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
 
Mathematical Preliminaries and Notation
=======================================

# Sets

A **set** is a collection of elements, without any structure other than membership.

The usual set operations are **union** ( <a href="https://www.codecogs.com/eqnedit.php?latex=\cup" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\cup" title="\cup" /></a> ), **intersection** ( <a href="https://www.codecogs.com/eqnedit.php?latex=\cap" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\cap" title="\cap" /></a> ), **difference** ( <a href="https://www.codecogs.com/eqnedit.php?latex=-" target="_blank"><img src="https://latex.codecogs.com/gif.latex?-" title="-" /></a> ) and **complementation** defined as

<a href="https://www.codecogs.com/eqnedit.php?latex=\begin{align*}&space;S_{1}&space;\cup&space;S_{2}&space;&=&space;\{\&space;x&space;:&space;x&space;\in&space;S_{1}\&space;{\rm&space;or}\&space;x&space;\in&space;S_{2}\&space;\},&space;\\&space;S_{1}&space;\cap&space;S_{2}&space;&=&space;\{\&space;x&space;:&space;x&space;\in&space;S_{1}\&space;{\rm&space;and}\&space;x&space;\in&space;S_{2}\&space;\},&space;\\&space;S_{1}&space;-&space;S_{2}&space;&=&space;\{\&space;x&space;:&space;x&space;\in&space;S_{1}\&space;{\rm&space;and}\&space;x&space;\notin&space;S_{2}\&space;\},&space;\\&space;\overline{S}&space;&=&space;\{\&space;x&space;:&space;x&space;\in&space;U,\&space;x&space;\notin&space;S&space;\&space;\}.&space;\end{align*}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\begin{align*}&space;S_{1}&space;\cup&space;S_{2}&space;&=&space;\{\&space;x&space;:&space;x&space;\in&space;S_{1}\&space;{\rm&space;or}\&space;x&space;\in&space;S_{2}\&space;\},&space;\\&space;S_{1}&space;\cap&space;S_{2}&space;&=&space;\{\&space;x&space;:&space;x&space;\in&space;S_{1}\&space;{\rm&space;and}\&space;x&space;\in&space;S_{2}\&space;\},&space;\\&space;S_{1}&space;-&space;S_{2}&space;&=&space;\{\&space;x&space;:&space;x&space;\in&space;S_{1}\&space;{\rm&space;and}\&space;x&space;\notin&space;S_{2}\&space;\},&space;\\&space;\overline{S}&space;&=&space;\{\&space;x&space;:&space;x&space;\in&space;U,\&space;x&space;\notin&space;S&space;\&space;\}.&space;\end{align*}" title="\begin{align*} S_{1} \cup S_{2} &= \{\ x : x \in S_{1}\ {\rm or}\ x \in S_{2}\ \}, \\ S_{1} \cap S_{2} &= \{\ x : x \in S_{1}\ {\rm and}\ x \in S_{2}\ \}, \\ S_{1} - S_{2} &= \{\ x : x \in S_{1}\ {\rm and}\ x \notin S_{2}\ \}, \\ \overline{S} &= \{\ x : x \in U,\ x \notin S \ \}. \end{align*}" /></a>

**DeMorgan's laws**

<a href="https://www.codecogs.com/eqnedit.php?latex=\begin{align*}&space;\overline{S_{1}\cup&space;S_{2}}&space;&=&space;\overline{S}_{1}&space;\cap&space;\overline{S}_{2},&space;\\&space;\overline{S_{1}\cap&space;S_{2}}&space;&=&space;\overline{S}_{1}&space;\cup&space;\overline{S}_{2}.&space;\end{align*}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\begin{align*}&space;\overline{S_{1}\cup&space;S_{2}}&space;&=&space;\overline{S}_{1}&space;\cap&space;\overline{S}_{2},&space;\\&space;\overline{S_{1}\cap&space;S_{2}}&space;&=&space;\overline{S}_{1}&space;\cup&space;\overline{S}_{2}.&space;\end{align*}" title="\begin{align*} \overline{S_{1}\cup S_{2}} &= \overline{S}_{1} \cap \overline{S}_{2}, \\ \overline{S_{1}\cap S_{2}} &= \overline{S}_{1} \cup \overline{S}_{2}. \end{align*}" /></a>

A set <a href="https://www.codecogs.com/eqnedit.php?latex=S_{1}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S_{1}" title="S_{1}" /></a> is said to be a **subset** of <a href="https://www.codecogs.com/eqnedit.php?latex=S" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S" title="S" /></a> if every element of <a href="https://www.codecogs.com/eqnedit.php?latex=S_{1}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S_{1}" title="S_{1}" /></a> is also an element of <a href="https://www.codecogs.com/eqnedit.php?latex=S" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S" title="S" /></a>. We write this as

<a href="https://www.codecogs.com/eqnedit.php?latex=S_{1}&space;\subseteq&space;S" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S_{1}&space;\subseteq&space;S" title="S_{1} \subseteq S" /></a>.

If <a href="https://www.codecogs.com/eqnedit.php?latex=S_{1}&space;\subseteq&space;S" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S_{1}&space;\subseteq&space;S" title="S_{1} \subseteq S" /></a>, but <a href="https://www.codecogs.com/eqnedit.php?latex=S" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S" title="S" /></a> contains an element not in <a href="https://www.codecogs.com/eqnedit.php?latex=S_{1}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S_{1}" title="S_{1}" /></a>, we say that <a href="https://www.codecogs.com/eqnedit.php?latex=S_{1}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S_{1}" title="S_{1}" /></a> is a **proper subset** of <a href="https://www.codecogs.com/eqnedit.php?latex=S" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S" title="S" /></a>; we write this as

<a href="https://www.codecogs.com/eqnedit.php?latex=S_{1}&space;\subset&space;S" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S_{1}&space;\subset&space;S" title="S_{1} \subset S" /></a>.

If <a href="https://www.codecogs.com/eqnedit.php?latex=S_{1}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S_{1}" title="S_{1}" /></a> and <a href="https://www.codecogs.com/eqnedit.php?latex=S_{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S_{2}" title="S_{2}" /></a> have no common element, then the sets are said to be **disjoint**. We write this as

<a href="https://www.codecogs.com/eqnedit.php?latex=S_{1}&space;\cap&space;S_{2}&space;=&space;\varnothing" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S_{1}&space;\cap&space;S_{2}&space;=&space;\varnothing" title="S_{1} \cap S_{2} = \varnothing" /></a>.

A set is said to be **finite** if it contains a finite number of elements; otherwise it is **infinite**.

The set of all subsets of a set <a href="https://www.codecogs.com/eqnedit.php?latex=S" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S" title="S" /></a> is called the **powerset** of <a href="https://www.codecogs.com/eqnedit.php?latex=S" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S" title="S" /></a> and is denoted by <a href="https://www.codecogs.com/eqnedit.php?latex=2^{S}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?2^{S}" title="2^{S}" /></a>. If <a href="https://www.codecogs.com/eqnedit.php?latex=S" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S" title="S" /></a> is finite, then

<a href="https://www.codecogs.com/eqnedit.php?latex=|2^{S}|&space;=&space;2^{|S|}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?|2^{S}|&space;=&space;2^{|S|}" title="|2^{S}| = 2^{|S|}" /></a>.

\begin{equation*}
S_{1} = S_{2}.
\end{equation*}

The elements of a set are ordered sequences of elements from other sets

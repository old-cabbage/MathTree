#Theorem 
(Cayley): Every [[Group]] $G$ of order $n$ is isomorphic to a [[Subgroup]] of S$_n$ 

Proof: The Rearrangement Lemma provided us with the correspondence from $G$ to S$_n:$
$$a \in G \longrightarrow p_a = \begin{pmatrix} 1 & 2 & \cdots & n \\ a_1 & a_2 & \cdots & a_n \end{pmatrix} \in S_n \qquad (1)$$
where the indices $\{a_i\}$ are determined from the defining identity (cf. footnote 1 after the Rearrangement Lemma):
$$g_{a_i} \equiv a g_i, \qquad i = 1, 2, \ldots, n \qquad (2)$$
Let $ab=c$ in $G.$ We have correspondingly,

$$\begin{aligned}p_{a}p_{b}&=\begin{pmatrix}1&2&\cdots&n\\a_1&a_2&\cdots&a_n\end{pmatrix}\cdot\begin{pmatrix}1&2&\cdots&n\\b_1&b_2&\cdots&b_n\end{pmatrix}\\&=\begin{pmatrix}b_1&b_2&\cdots&b_n\\a_{b_1}&a_{b_2}&\cdots&a_{b_n}\end{pmatrix}\cdot\begin{pmatrix}1&2&\cdots&n\\b_1&b_2&\cdots&b_n\end{pmatrix}=\begin{pmatrix}1&2&\cdots&n\\a_{b_1}&a_{b_2}&\cdots&a_{b_n}\end{pmatrix}\quad.\\\end{aligned}$$

$\textbf{But according to Eq. (2), }$


$$g_{a_{b_{i}}}=ag_{b_{i}}=a(bg_{i})=(ab)g_{i}=cg_{i}=g_{c}\quad(3)$$

We conclude that the right-hand side of the above equation is just

$$p_c=\begin{pmatrix}1&&2&\cdots&n\\c_1&&c_2&\cdots&c_n\end{pmatrix}\quad.$$

Hence,  $ab= c$ in $G$ implies $p_{a}p_{b}= p_{c}$ in $S_{n}$;  in other words,  the mapping $a\in G\to$ $p_{a}\in \mathcal{S} _{n}$ preserves group multiplication.  It follows that the permutations


$$p_a=\begin{pmatrix}1&2&\cdots&n\\a_1&a_2&\cdots&a_n\end{pmatrix}$$

for all $a\in G\text{ form a subgroup of S}_n$ which is isomorphic to $G.$ $QED$

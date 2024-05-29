<h4>Basic Set Facts and Algebra</h4>
Theorems should be proven by the reader (I'll distinguish definitions, axioms, and theorems later)
{% raw %}
<ul>
    
<li>
  Set, element (\(\in ,\  \notin\)), universal set
</li>
<li>
  The empty set: \(\varnothing = \{ x\  \mid\ x\ satisfies\ an\ impossible\ condition \}\)
</li>
<li>
  Equality of sets; A = B
</li>
<li>
  Complements, \(\overline{\overline{A}} = A\)
</li>
<li>
  \(A \cup B,\ A \cap B,\ A - B = A \cap \overline{B}\)
</li>
<li>
  \(\bigcup_{}^{}A_{i},\ \bigcap_{}^{}A_{i}\)
</li>
<li>
  DeMorgan, extension of DeMorgan to multiple intersections and unions
</li>
<li>
  Subsets: \(A \subseteq B, A \subset B, A \supseteq B, A \supset B\)
  <ul>
    <li>\(A = B\ \) iff \(A \subseteq B\ \small\mathsf{AND}\normalsize\ A \supseteq B\)</li>
    <li>\(A \subseteq A \cup B, B \subseteq A \cup B\)</li>
    <li>\(A \cap B \subseteq A, A \cap B \subseteq B\)</li>
    <li>\(A \subseteq B\ \) iff \(A \cap B = A\)</li>
    <li>\(A \subseteq B\ \) iff \(\overline{B} \subseteq \overline{A}\)</li>
    <li>\(A - B = \varnothing \) iff \(A \subseteq B\)</li>
    <li>There is <u>NOT</u> a subset trichotomy law!!
      <br>
      \(A \subseteq B, B \subseteq A \ and\ A = B\) may all be false!
    </li>
  </ul>
</li>
<li>Special Differences:</li>
  <ul>
    <li>\(A - B = \varnothing \) iff \(A \subseteq B\)</li>
    <li>\(A - B = A \) iff \(A \cap B = \varnothing \) iff \(B - A = B\)</li>
    <li>\(A - B = B \) iff \(A = B = \varnothing \)</li>
  </ul>
<li>\(A \cap B = \varnothing \) iff \(A \subseteq \overline{B} \) iff \(B \subseteq \overline{A} \)
    <br>
    (BE CAREFUL!  This does NOT imply that \(\overline{A} \subseteq B \) or \(\overline{B} \subseteq A \))
</li>
<li>\(C \subseteq A\ \small\mathsf{AND}\normalsize\ C \subseteq B \) iff \( C \subseteq A \cap B\)</li>
<li>if \(C \subseteq A\ \small\mathsf{AND}\normalsize\ C \subseteq B\), then \(C \subseteq A \cap B\)
<br>if \(C \subseteq A\ \small\mathsf{OR}\normalsize\ C \subseteq B\), then \(C \subseteq A \cup B\)
<br>The converse of the above two statements need not be true. To see this, consider 
    <br>
    \(C = \{x, y\}, A = \{x\}, B = \{y\} \)
</li>
<li>\(A \subseteq C\ \small\mathsf{OR}\normalsize\ B \subseteq C \) iff \(A \cup B \subseteq C \)</li>
<li>if\(A \subseteq C\ \small\mathsf{AND}\normalsize\ B \subseteq C\), then \(A \cap B \subseteq C\)
<br>if\(A \subseteq C\ \small\mathsf{OR}\normalsize\ B \subseteq C\), then \(A \cap B \subseteq C\)
<br>The converses of these statements need not be true
</li>
<li>if\(A \cap B = \varnothing\)
  <br>then \(A\cup B=C \Leftrightarrow C-A=B \Leftrightarrow C-B=A\)
</li>
<li> Equivalences of \(A \subseteq B\):
<br>\(A \subseteq B \Leftrightarrow 
    A \cap B = A \Leftrightarrow 
    A \cup B = B \Leftrightarrow 
    A - B = \varnothing \Leftrightarrow 
    A \cap \overline{B} = \varnothing \Leftrightarrow 
    \overline{B} \subseteq \overline{A}\)
</li>
</ul>
{% endraw %}

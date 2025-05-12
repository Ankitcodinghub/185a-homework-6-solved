# 185a-homework-6-solved
**TO GET THIS SOLUTION VISIT:** [185A Homework 6 Solved](https://www.ankitcodinghub.com/product/185a-homework-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91033&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;185A Homework 6 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Instructions: Download CFG.hs and Assignment06.hs from the course web- site into the same directory on your computer. The import line near the top of Assignment06.hs imports all of the de
nitions from CFG.hs, which you may then use in your assignment. You should familiarize yourself with everything in CFG.hs before beginning the assignment. Please submit your assignment as a modi
ed version of Assignment06.hs.


 
 points For warm-up practice with some of the relevant types, please code up the following

functions:

<ul>
<li>(
) &nbsp;terminalsOnly, which tries to convert a mixed string of nonterminal and terminal symbols into a string of just terminal symbols. If the given string contains no nonterminal symbols, then the result should be a Just value with the list of whatever terminal symbols the given string contains. If the given string contains nonterminal symbols, then the result should be Nothing.
Example usage:


⇒∗

terminalsOnly [T “John”, T “saw”, NT “NP”] 
⇒∗ Nothing
</li>
<li>(
) &nbsp;leaves, which returns the list of terminal symbols that appear at the leaves of the given tree, in order.
Example usage:


⇒∗

leaves (NonLeaf 0 (Leaf 0 a) (NonLeaf 0 (Leaf 0 b) (Leaf 0 c)))
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Ethan Poole 



 



: Comp. Ling. I Due: 

 May 





</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>terminalsOnly [T "John", T "saw", T "Mary"]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>leaves (NonLeaf "S" (Leaf "NP" "Mary") (Leaf "VP" "ran"))
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Just [“John”, “saw”, “Mary”]

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>["Mary", "ran"]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">

⇒∗ “abc” Page 
 of 


</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">

 

 points Please code up the following functions that convert between trees, rule lists, and

derivations:

(
) treeToRuleList, which returns the list of rules used in the leftmost derivation corresponding to the given tree, in the order in which they are used in that leftmost derivation.

Hint: All of the rewriting steps that construct parts of a node’s left daughter tree precede all of the rewriting steps that construct parts of that node’s right daughter tree . . .

treeToRuleList (NonLeaf “S” (Leaf “NP” “Mary”) (Leaf “VP” “ran”)) 
⇒∗ [NonterminalRule “S” (“NP”, “VP”), TerminalRule “NP” “Mary”, TerminalRule “VP” “ran”]

treeToRuleList (NonLeaf 1 (NonLeaf 2 (Leaf 4 a) (Leaf 5 b)) (Leaf 3 c)) 
⇒∗

[NonterminalRule 1 (2,3), NonterminalRule 2 (4,5), TerminalRule 4 a, TerminalRule 5 b, TerminalRule 3 c]

treeToRuleList (NonLeaf 1 (Leaf 2 a) (NonLeaf 3 (Leaf 4 b) (Leaf 5 c))) 
⇒∗

[NonterminalRule 1 (2,3), TerminalRule 2 a, NonterminalRule 3 (4,5), TerminalRule 4 b, TerminalRule 5 c]

(
) ruleListToTree, which is, in e
ect, the reverse of treeToRuleList. If the given list of rules does not correspond to any leftmost derivation, then the result should be Nothing. If the given list of rules does correspond to a leftmost derivation, the result should be a Just value containing the appropriate tree.

What is intended by “leftmost derivation” is a sequence of steps from a single nonterminal symbol to a string containing only terminal symbols. As this is not relative to any particular grammar, it does not matter what nonterminal symbol the derivation starts from; this will just be whatever nonterminal symbol happens to appear on the left-hand side of the 
rst rule in the list.

Page 
 of 


</div>
</div>
<div class="layoutArea">
<div class="column">
Example usage:

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Example usage:


⇒∗

ruleListToTree [NonterminalRule 1 (2,3), TerminalRule 2 a, NonterminalRule 3 (4,5), TerminalRule 4 b]

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>ruleListToTree [NonterminalRule "S" ("NP", "VP"), TerminalRule "NP" "Mary", TerminalRule "VP" "ran"]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Just (NonLeaf “S” (Leaf “NP” “Mary”) (Leaf “VP” “ran”))

</div>
</div>
<div class="layoutArea">
<div class="column">

⇒∗ Nothing

</div>
</div>
<div class="layoutArea">
<div class="column">
(
) treeToDerivation, which returns the leftmost derivation corresponding to the given tree, in the form of a list of mixed strings containing terminal and nonterminal symbols. Note that because this is a derivation, the order matters!

You must not execute this function by 
rst recovering the list of rules used in the derivation and then carrying out the rewriting steps one by one. There is a much more elegant and clever way to construct the necessary strings directly from the tree structure.

Example usage:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>treeToDerivation (NonLeaf "S" (Leaf "NP" "Mary") (Leaf "VP" "ran"))
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">

⇒∗

treeToDerivation (NonLeaf 1 (NonLeaf 2 (Leaf 4 a) (Leaf 5 b)) (Leaf 3 c))

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>[[NT "S"], [NT "NP", NT "VP"], [T "Mary", NT "VP"], [T "Mary", T "ran"]]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">

⇒∗ [[NT 1],[NT 2,NT 3],[NT 4,NT 5,NT 3],[T a,NT 5,NT 3],[T a,T b,NT 3],[T a,T b,T c]] 
 

 points

</div>
</div>
<div class="layoutArea">
<div class="column">
The rewrite and splitAtNT functions provided in CFG.hs, which we discussed in class, capture the basic idea of what a rewriting step looks like. However, that particular rewrite function does not necessarily carry out the kinds of steps that appear in leftmost derivations. It rewrites, fairly arbitrarily, the leftmost occurrence (if there is one) of the particular nonterminal symbol to which the given rule can apply. This will not in general be the leftmost nonterminal symbol in the string.

Please code up the following functions that in e
ect, carry out all the leftmost derivations allowed by a grammar. Note that the rewrite and splitAtNT functions might be useful starting points to think about.

Page 
 of 


</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
<ul>
<li>(
) &nbsp;splitAtLeftmost, which splits a list of symbols at the leftmost occurrence of a nonterminal symbol. The idea is to use this function to pick out the position where the next rewriting step will happen in a leftmost derivation. If there are no nonterminal symbols in the list, then the result should be Nothing. Otherwise, it should be a Just value containing a triple, which has the leftmost nonterminal symbol itself as its second component, and has the preceding and following parts of the list as the 
rst and third components respectively.
Example usage:


⇒∗

splitAtLeftmost [T “apples”, T “and”, T “oranges”, T “or”, T “bananas”]
</li>
<li>(
) &nbsp;rewriteLeftmost, which rewrites the leftmost nonterminal symbol in the given list of symbols, in all the ways possible according to the given list of rules. Each such possible rewriting step produces a new list of symbols. The result should be a list containing all of these resulting lists of symbols. In the following examples, snd is used to extract the second component of a pair, here, for the purposes of retrieving a CFG’s list of rules.

⇒∗
</li>
<li>(
) &nbsp;derivableFrom, which produces all the strings of terminals that can be derived from the given mixed string of terminals and nonterminals, using the given list of rules, in at most the given number of steps. The order in which the strings of terminals appear in the resulting list does not matter. However, you should only consider leftmost derivations. Therefore, a string of terminals should appear in the result list more than once if and only if there are multiple distinct leftmost derivations of that string.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>splitAtLeftmost [T "apples", T "and", NT "NP", T "or", NT "NP"]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Just ([T “apples”, T “and”], “NP”, [T “or”, NT “NP”])

</div>
</div>
<div class="layoutArea">
<div class="column">
Example usage:

</div>
</div>
<div class="layoutArea">
<div class="column">
rewriteLeftmost (snd cfg1) [NT “NP”, NT “VP”] 
⇒∗

[[NT “D”, NT “N”, NT “VP”], [T “John”, NT “VP”], [T “Mary”, NT “VP”]]

</div>
</div>
<div class="layoutArea">
<div class="column">

⇒∗ Nothing

</div>
</div>
<div class="layoutArea">
<div class="column">
rewriteLeftmost (snd cfg1) [T “John”, NT “VP”]

</div>
</div>
<div class="layoutArea">
<div class="column">
Hint: Remember terminalsOnly!

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>[[T "John", NT "V", NT "NP"]]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 
 of 


</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Example usage:

</div>
</div>
<div class="layoutArea">
<div class="column">
derivableFrom [NT “NP”] (snd cfg1) 0 
⇒∗ [] derivableFrom [NT “NP”] (snd cfg1) 3 
⇒∗

[[“the”,”cat”],[“the”,”dog”],[“a”,”cat”],[“a”,”dog”],[“John”],[“Mary”]] derivableFrom [T “Mary”, NT “VP”] (snd cfg1) 2 
⇒∗ []


⇒∗

From here, you could write the one-line function to 
nd all strings derivable via a

</div>
</div>
<div class="layoutArea">
<div class="column">
derivableFrom [T “Mary”, NT “VP”] (snd cfg1) 3

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>[["Mary","saw","John"],["Mary","saw","Mary"],
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>["Mary","likes","John"], ["Mary","likes","Mary"]]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
given grammar, up to a maximum number of steps: (
)

</div>
</div>
<div class="layoutArea">
<div class="column">
derivable :: (Eq nt, Eq t) =&gt; CFG nt t -&gt; Int -&gt; [[t]] derivable (start , rules) n =

derivableFrom [NT start] rules n

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 
 of 


</div>
</div>
</div>

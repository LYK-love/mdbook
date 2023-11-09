# Why ZFC?

这学期选了门Information Theory的课, 惊觉自己的Probability Theory(概率论)基础还不扎实, 遂补了许多Probability Theory的知识. Probability Theory是以Measure Theory作为其基础的. Measure Theory本身又是对集合的measure()测度这一性质的讨论. 因此, here we go, 又回到了最fundamental的Set Theory.

现代集合论就是ZFC公理化集合论, 这其中有三个令人争议的点:

1. 选择公理, 它导致了Lebesgue不可测集合的存在.
2. 无穷大的概念, 无穷大的集合所具有的性质是反直觉的. 
3. 排中律.

其中(3)我个人其实没有什么意见, 虽然constructivism反对它, 但它十分符合直觉, 因此就采纳了. 

我困惑的点主要是(1)和(2), 这两个问题本身也是相关的: 对于有穷集合, 选择公理自然没什么问题; 可对于无穷集合, 这就会导致一些反直觉的结论.

我的问题是: 为什么我们要接纳(1)和(2), 将其作为集合论的公理[^1]? 是因为真的有这个东西(无穷, 还有选择公理这些东西), 我们才去承认它, 把它作为公理; 还是说因为它仅仅好用, 或者符合审美?

更进一步, 我想质疑数学中"公理化"这一行为的动机. 对数学公理化的后果解释的很清楚: 

> The progress achieved by axiomatics consists in its having neatly **separated the logical-formal from its objective or intuitive content**; according to axiomatics the logical-formal alone forms the subject-matter of mathematics, which is **not concerned with the intuitive or other content associated with the logical-formal.**

数学在公理化后, 其内容应在纯粹形式意义上理解，*即*不包含任何直觉或经验的内容。

现代公理学所倡导的这种公理观清除了数学中所有无关的元素，从而消除了以前围绕数学原理的神秘晦涩。但是，如此澄清的其原理的表述也表明，数学本身不能预测任何关于感知对象或真实对象的事情. 公理化几何中, 点, 线等词语仅代表空洞的概念图式, 赋予它们实质内容的东西与数学无关。

> This view of axioms, advocated by modern axiomatics, purges mathematics of all extraneous elements, and thus dispels the mystic obscurity which formerly surrounded the principles of mathematics. But a presentation of its principles thus clarified makes it also evident that mathematics as such cannot predicate anything about perceptual objects or real objects. In axiomatic geometry the words "point," "straight line," etc., stand only for empty conceptual schemata. That which gives them substance is not relevant to mathematics.





在我看来有两种可能:

1. 所谓的数学对象, 真的是独立于人类而永恒存在的柏拉图式的真理. 

   > mathematics exists independently of humans in some kind of *[Platonic](https://en.wikipedia.org/wiki/Platonism)* realm of eternal truth, which we venture out to explore with our minds.

   然后我们试图通过公理化, 寻找到一些公理, 让它们尽可能接近这些绝对真理. 

2. 数学仅仅是工具, 是一种逻辑上的游戏(a game of pure logic), 是自身没有意义的计算. 

如果选择(1), 那么"公理化"这一行为, 连带着数学领域的所有行为, 都是自成其意义的, 它的意义就是逼近"绝对真理". 但(1)所代表的柏拉图式的世界观本身是否成立都是个问题.

如果选择(2), 那就相当于不承认数学自身的意义, 仅把它当作为科学服务的工具学科来对待了. 那会产生两个问题; 

3. 首先, 数学归根结底不过是一种独立于经验的人类思维, 为什么能够如此令人叹服地适用于真实世界中的对象? 那我们可以说, 人类的理性, 不依赖经验而只采用思考, 就可以推测真实事物的性质吗?

   > At this point an enigma presents itself which in all ages has agitated inquiring minds. How can it be that mathematics, being after all a product of human thought which is independent of experience, is so admirably appropriate to the objects of reality? Is human reason, then, without experience, merely by taking thought, able to fathom the properties of real things. --Einstein, An expanded form of an Address to the Prussian Academy of Sciences in Berlin on January 27th, 1921

4. 同样的, 科学在我看来也就是以数学为工具, 再加上一些人造的(或者说, 人类根据自己的经验总结出的)方法论组成的另一个工具, 它也是人造的. 那么, 为什么科学这个人造的东西, 真的能帮助我们理解这个世界(这应当是个明显的论断), 科学theorem几乎就是自然界的ground trueth, 总是被实验支持呢?

   > "The eternal mystery of the world is its comprehensibility... **The fact that it is  comprehensible is a miracle.**" --Einstein, "Physics and Reality," Journal of the Franklin Institute (Mar. 1936), in Einstein, 1954, Ideas and  Opinions.

这个问题太宏大了, 不是现在的我能弄清楚的. 

# What is Axiom

The word “axiom” in ancient greek meant “that which is to be assumed” or “that which is thought worthy”. An axiom is always *an assumption,* although over some 2500 years its meaning gradually morphed into  meaning an assertion so obviously true that no further proof was  necessary. 

在后来的数学发展中, 人们一再认识到第二种认知是错误的, 哥德尔后来证明了不存在第一个意义上的公理化系统, 因此"公理"的含义应该取第一种. 

This is *why* mathematicians more often refer to axioms as postulates these days. The original definition was corrupted by time during the substantial  interval when plane geometry was taught as “manifestly true” knowledge  of the real world. The word postulate — like the world axiom originally — makes it clear that the foundations for mathematical reasoning are *assumptions,* not *manifest truths.*



# Nothing in Physics Requires AC

幸运的是, 在可见的未来, 我似乎不需要处理关于无穷大和选择公理的问题. 根据[StackExchange的这篇回答](https://physics.stackexchange.com/questions/43853/are-there-physical-theories-that-require-the-axiom-of-choice-to-be-true-to-wor), Nothing in Physics Requires AC:

However, nothing in physics depends on the validity of the axiom of choice  because physics deals with **the explanation of observable phenomena**.  

**Infinite collections of sets** – and they're the issue of the axiom of  choice – **are obviously not observable** (we only observe a finite number  of objects), so experimental physics may say nothing about the validity  of the axiom of choice. If it could say something, it would be very  paradoxical because axiom of choice is about pure maths and moreover,  maths may prove that both systems with AC or non-AC are equally  consistent.

Theoretical physics is no different because it deals with various  well-defined, "constructible" objects such as spaces of real or complex  functions or functionals.



> No, nothing in physics depends on the validity of the axiom of choice  because physics deals with the explanation of observable phenomena.  Infinite collections of sets – and they're the issue of the axiom of  choice – are obviously not observable (we only observe a finite number  of objects), so experimental physics may say nothing about the validity  of the axiom of choice. 

No, nothing in physics depends on the validity of the axiom of choice  because physics deals with the explanation of observable phenomena.  Infinite collections of sets – and they're the issue of the axiom of  choice – are obviously not observable (we only observe a finite number  of objects), so experimental physics may say nothing about the validity  of the axiom of choice. If it could say something, it would be very  paradoxical because axiom of choice is about pure maths and moreover,  maths may prove that both systems with AC or non-AC are equally  consistent.

# Physics as an Epistemology

下面的观点引用自[Quora](https://www.quora.com/Are-there-axioms-in-physics-that-just-have-to-be-accepted-to-be-true).

*All* systems of reasoning **are built on top of unprovable things that are assumed to be true, on top of axioms, or postulates, or propositions**, as well as things like definitions and operational rules that are themselves a form of postulate. Physics as an epistemology built on top of mathematics therefore is built on top of things that are assumed to be true, on axioms/postulates/definitions/rules.

# No Axiom in Physics

There is one enormous difference between mathematics and physics, however. In physics those axioms are always considered not “truth”, or even “assumed truth in a way that cannot be challenged”, they are considered to be *provisional* truths, upon which a system of *contingent* reasoning is built with the requirement that the system maintain the *maximum congruence possible with empirical observations of reality.* In this system of reasoning, it is actually marginally incorrect to call the fundamental hypotheses of physics *either* postulates *or* axioms, per se. Rather they are **Bayesian priors** allowing us to make predictions about the *probable* behavior of reality and subject to revision in recomputations of posterior probability if and when evidence that *contradicts* them emerges.

在物理学中, 如果实验发现了反例, 那么我们直接推翻了 *provisional* truth, 没有绝对正确的前提. 但是在数学中, 前提是不可推翻的, 它确实只是postulate, 不是什么ground truth, 但我们直接承认它.



Example: Historically, it was assumed *beyond question* that space had to be Euclidean and flat, because, well, it just was,  and Euclid’s geometry was just plain true. Then along came curved space  geometry, and for a comparatively brief time it was still something one  could shrug off, reality *still* had to be flat space because, well, you could measure and sum the angles in triangles and they still added up to *𝜋*. But then along came Einstein, and general relativity, and measurements  of actual phenomena in space and time that could (so far!) only be  explained by curvature of spacetime, where the sum of the angles in  triangles formed by three geodesics did *not* add up to *𝜋*. Physical science at that point was forced to *change* its “axioms”. It had to change them again, this time far more, when  classical physics was rejected — on the basis of evidence — for quantum  physics. It may have to change them again… and again… in the future as  evidence requires.

# Nature of Science

https://yueyao1982.com/reconstr_phil/preface.html#id6

背负解释世界本质任务的哲学，在当代失灵了。 想了解世界的本质，现在大家更倾向于去问科学家。 科学能解答很多问题，但科学能解答的所有问题，都是事物和事物之间关系的问题。 对于事物本身是什么，它们是无能为力的。 比如我们要认识一个桌子，我们称它为*𝑥*。 通过科学，我们可以认识关于*𝑥*的各种函数：比如*𝑠*(*𝑥*)可以代表*𝑥*的形状， *𝑐*(*𝑥*)可以代表*𝑥*的颜色或者在*𝑠*(*𝑥*)上的颜色分布，凡此种种。 但要说关于*𝑥*本身，科学是无能为力的。 归根结底，这是因为科学的语言是数学，而数学不研究对象本身而只研究对象之间的关系，确切的说，归根结底都是对象的量之间的关系。 比如我们在写 *𝑥*+*𝑥*=2*𝑥*时，我们的意思可以是一个桌子的长度加上另一个长度相等的桌子的长度是两倍它的长度， 可以是一个桌子的体积加上另一个体积相等的桌子的体积是两倍它的体积，但绝不是一个桌子加上它自身等于两倍的它自身。 如果*𝑥*和*𝑦*代表桌子，而不代表任何和桌子有关的量， 那么*𝑥*=*𝑦*意味着两个桌子所有的性质都要相等，包括他们占据的空间，那*𝑥*和*𝑦*也必然是同一张桌子，*𝑥*+*𝑦*=2*𝑥*

也是无意义的。 所以一切科学研究的对象都是量，它们可以是标量、矢量甚至张量，但从来不是对象本身。 用叔本华的话来说就是，在作为表象的世界里，物质的存在就在于它们的作用：用更为现代的语言来说，是桌子和其他物体之间的作用函数。 我们不能认识桌子本身，我们只能认识它看起来什么样（与我们之间的视觉作用），它摸起来什么样（与我们触觉之间的作用）， 它闻起来怎么样（与我们嗅觉之间的作用），用仪器观测起来怎么样（桌子与仪器，以及仪器与我们之间的作用）。

科学对世界的解释是还原论的。 我们问桌子是什么，就可以把桌子切开看，最后得出桌子是由分子/原子构成的，分子/原子又是由基本粒子构成的，而基本粒子是什么，又很难说得清楚。 经过一系列的还原，我们还是找不到“桌子是什么”这个问题的答案。 有人可能会说，“桌子是什么”这种问题本身可能就是无意义的，我们只要知道它是由什么构成的就好了。 可是“桌子”除了物体又是一个概念，而问“一个概念是什么”不可能是无意义的。 本书要讨论的另一个重要问题就是“概念是如何形成的”。

有人说，我们现在要说的是实际上的桌子，而不是你说的概念上的桌子。 那好，如果我们得到所有关于桌子与其他所有物体的作用函数，是不是我们就完全认识桌子了呢？ 这听起来好像也可以接受。 但正如叔本华指出的那样：我们可以把事物认为是与它有关所有作用的集合，直到我们认识我们自己。 难道有人会认为，“我的存在就是我和周围所有事物的相互作用的总和吗”？ 所以，至少在认识“我是什么”这个问题上，科学失效了。



物理学家只能描述“物理世界是什么样的”或者“物理模型是什么样的”，因为“物理世界”是他们唯一关心的世界。 严格来说，他们并**不关心“物理世界的本质是什么”**，更别说“世界的本质是什么”了。 虽然这个过程他需要使用数学，但大部分的物理学家也不关心“数学的本质是什么”。

## 大爆炸理论



一个更有意思的例子是“大爆炸理论”。 有些物理学家说：大爆炸之前是不能问的，因为它定义了时间的开始。 对此，很多人都感到惊愕，这些物理学家表现的又极像“独裁者”。 物理学家其实至多可以说：在我用来描述现今宇宙的模型里有一个奇点，而在这个模型里，这个奇点也定义了当前这个世界时间的起点；在我这个模型里，奇点以前是什么样子的，是无法从后面的事件推测出来的。 这当然可以有很多可能性：奇点可能隔绝了现代时空的“前时空”，甚至奇点外面也不一定空空如也：难道有任何理由阻止我们把这个时空内嵌到一个更大的、甚至是更高维的时空里去？ 科学家要严谨的表达他自己的理论这很好，可是他使用的自然语言却是极为不严谨的，他甚至为了科学的严谨牺牲了更高的哲学上和逻辑学上的严谨。 但是为什么科学家会犯错误呢？ 因为他其实不了解“世界”有很多的指向，他描述的那个“世界”只是指向他的大爆炸模型。 除此之外，“世界”还可以有很多指向。 甚至连“物理世界”也可以包含很多指向：他所描述的“世界”只是在所有的“物理世界”里，在他关心的时空范围里，符合大爆炸模型的“最小”的世界。 他选择去描述这个“最小世界”，那仅仅是他个人的审美偏好，正像“奥卡姆剃刀原理”，严格来说其实不是原理，只是一种逻辑的审美倾向。 物理学家可以选择去剔除他觉得冗余无用的东西，但如果他强行把他的审美趣味强加在其他人身上，却并没有正当性， 因为那些人的关注点和他不一定一样，人家想知道的“世界的本质”说不定更多的是被他剔除的细节，因为他剔除的细节只是在他所关注的物理问题上无用的细节。 我们可以用[芝诺悖论](https://baike.baidu.com/item/芝诺悖论)里的阿基里斯追不上乌龟的问题作个比照。 芝诺争辩说，阿基里斯永远也追不上乌龟，因为在他建构了一个无限的步骤，而且在这个无限的步骤里，阿基里斯都没有追上乌龟。 用现代数学的眼光来看，这个一个很简单的问题。 它只是一个等比数列的收敛问题：比如无穷级数∑*𝑖*=0∞12*𝑖*虽然是无穷个项相加，但结果却不是无穷而是2这个实数。 但试想，如果存在一种智能生物，他们对时间的感觉是非线性的，更具体的来说，我们感觉的时间(*𝑡*)和他们感觉的时间(*𝑇*)之间有如下的映射*𝑇*(*𝑡*)
$$
T(1)=1,\, T\left(1+\frac{1}{2}\right)=2,\, T\left(1+\frac{1}{2}+\frac{1}{4}\right)=3,\, \ldots
$$
它最自然的一个解是
$$
T=1+\log_2 \frac{1}{2-t}.
$$


那样的话，我们时间体系中的2

就是他们时间体系中的无穷。 他们那个物种中的物理学家也完全可以说：“我们世界中2所代表的时间是达不到的，问2之后的时间是什么， 是没有意义的：你甚至根本就不能问这样的问题。” 这个虚拟世界中严谨的物理学家说得完全没有问题，但他的视野过于局限于他那个世界，他那个模型。 而我们是如此的幸运，因为我们的理智具有超越的本质：它可以超越三维空间，它甚至可以研究无穷维空间。 有人想把自己的思考专注在他目前可以严格分析的事物上，这没什么问题； 但同时，有人想知道在这些事情之外有什么样的可能性，这同样也没什么问题。



http://www.relativitybook.com/resources/Einstein_geometry.html


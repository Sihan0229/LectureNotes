Lecture Videos Links: [Bilibili](https://www.bilibili.com/video/BV1te4y1t7yL/?spm_id_from=333.1387.favlist.content.click&vd_source=3eea97cca726b52e31eba5c50a723cb0)/[Youtube](https://www.youtube.com/playlist?list=PLUl4u3cNGP60IKRN_pFptIBxeiMc0MCJP)

Lecture Slice Link: [MIT Open Course Ware](https://ocw.mit.edu/courses/9-13-the-human-brain-spring-2019/pages/lecture-notes/)

# Lecture 1: Introduction

### Four Major Components of the Brain
- Brain stem & cerebellum 脑干和小脑
- Limbic system
(subcortical regions)
- White Matter
- Cerebral cortex (outer sheet)

### Important Subcortical Bits
**Thalamus 丘脑**
- 感觉中继站（relay station），起信息传递作用，多数感觉信息传入皮层前经此。嗅觉（olfaction）例外，不经过丘脑。
- 视觉中继：Lateral Geniculate Nucleus（LGN），负责视网膜（retina）到皮层视觉信息传递，从retinal ganglion cells接受信息，通过optic radiations传输到primary visual cortex (V1)。LGN主要位于thalamus的posteroventral region。 
- 反向连接：存在大量下行连接（如 V1 到 LGN 连接远多于反向）  

**Hippocampus 海马体**
- long-term memory
- spatial navigation

**Amygdala 杏仁核**
- 负责情感反应和恐惧的识别
- SM患者没有Amygdala，导致缺乏恐惧感。

**灰质（Grey Matter）**
- 由cell bodies组成，是信息处理的主要区域。

**白质（White Matter）**
- 主要由髓鞘化的轴突（myelinated axons）组成，负责不同区域之间的信号传输。
- The specific connections of each region may serve as a
“fingerprint” of that region across species, enabling us to
discover interspecies homologies
- Disruptions of white matter may be key to clinical disorders

# Lecture 2: Neuroanatomy
### 受体场 Receptive Field
- a region of visual space that drives a specific neuron in the cortex more than others.
- 通过固定猴子的眼睛并刺激不同区域，发现某些神经元对特定区域的刺激反应最强。不同神经元的受体场与空间位置、形状、颜色、运动方向等其他属性相关。

### Retinotopic Maps 视网膜映射
- 在视觉皮层中临近的区域，会对应视网膜中临近的区域。

### 视觉运动区 Visual motion area MT
Single neurons in MT are tuned to the direction of motion. Nearby neurons within MT have similar directional selectivity.

- **Microstimulation**：在MT区域进行微刺激，刺激结果影响运动感知
- **Lesions 损伤**：双侧MT损伤的患者会丧失运动感知能力：运动失认症（Akinetopsia）

#### 大脑皮层区域的定义（以MT为例）

一个视觉皮层区域的定义标准包括功能特征、与其他区域的连接性以及细胞结构（cytoarchitecture）的不同。

A region of cortex distinct from its neighbors in **function**, **specific connectivity** and **cytoarchitecture**

- **功能**：selectivity/processing a specific dimension，MT区专门处理运动信息。通过single neurons in monkeys、fMRI、psychophysics、microstimulation、lesions in humans等，可以确认MT的功能。
- **连接性**：MT区域具有独特的connectivity fingerprint与其他区域连接。
- **细胞结构**：MT区域通过细胞色素氧化酶（cytochrome
oxidase）染色显示出较高的代谢活动，以表明MT在运动感知中的功能。

#### Brodmann区域

- **Korbinian Brodmann（1868-1918）**：根据皮层的细胞结构，Brodmann识别出52个不同的大脑区域，这些区域被视为大脑的“器官organs”。

# Lecture 4-5: Cognitive Neuroscience Methods

Methods in Cognitive Neuroscience Methods, & the Questions they answer, applied to face perception

这一章节以 face recognition 为例，通过六个问题的引导来探讨相关methods：

1. What is the nature of the problem of face perception? (inputs, outputs, challenges). 面孔知觉问题的性质
2. How does face recognition work in humans?
what computations, what representations?
is this answer different for face versus object reocognition? 人类是如何进行面部识别的？计算和表示方法是什么？和物体识别有什么区别？向
3. Is face perception a distinct system from the rest of vision/cognition? 面部识别是否与其他视觉/认知系统不同，是一个独立的系统？
4. How fast are faces detected and recognized? 面部检测与识别的速度？
5. How is face recognition implement in individual neurons/circuits? 面孔识别是如何在个别神经元/神经回路中实现的？
6. What is the causal role of each brain region in face recognition? 每个大脑区域在面孔识别中的因果作用是什么？

### Marr Computational Theory Level of Analysis （Marr计算理论分析层次）

用于解决 **问题1：What is the nature of the problem of face erception?**

Case study: Color Vision
- **计算理论 (Computational Theory)**  
   - **目标**：理解系统做什么，为什么做。
   - **问题**：提取什么信息？为什么？推理是否存在不适定（ill-posed）问题？
   - **色觉例子**：从光（L）中推断反射率（R），但反射率（R）是未知的，推理过程是不适定的。

- **算法/表示 (Algorithm/Representation)**  
   - **目标**：理解系统如何实现任务，使用什么算法或表示。
   - **问题**：如何完成任务？使用了什么假设？怎样的计算模型？
   - **色觉例子**：如何构建算法从光（L）推断反射率（R）。

- **硬件实现 (Hardware Implementation)**  
   - **目标**：理解系统如何通过硬件实现计算。
   - **问题**：如何在硬件上实现这些计算？
   - **色觉例子**：大脑如何通过神经网络实现这些推理任务？

**major challenge**: huge variation across images of a single face. 从而引出**问题2：How does face recognition work in humans?**，接下来引入Behavior解决问题2.

### Behavior: Strengths and Weakness of Behavioral Methods (low-tech)
- Good for characterizing internal representations and dissociating distinct mental phenomena.
- But no relationship to the brain. 
- Only the final stage output instead of each stage in whole precessing. (解决方案：fMRI)

这里Behavior和fMRI都在解答**问题3：Is face perception a distinct system from the rest of vision/cognition?**

### Functional Magnetic Resonance Imaging (fMRI)
- 原理：**BOLD signal**（blood oxygenation level dependent）表示与血液氧合状态相关的变化。神经活动增加时，局部的血流增加超过了氧气使用的需求，这导致局部的氧气浓度下降，脱氧血红蛋白deO2Hb（deoxygenated hemoglobin）浓度降低。氧合血红蛋白（O2Hb）和去氧血红蛋白（deO2Hb）在磁共振成像中呈现不同的信号特性。deO2Hb是顺磁性的，使得MR信号强度增加。
- Cannot measure absolute amounts of activity/metabolism, only differences between two conditions.
- Physiological basis of the BOLD signal is unknown
- fMRI suggests that distinct neural tissue is engaged in face vs object recognition. 面部识别和物体识别使用的是不同的神经组织。
- Can’t tell if activity measured plays a causal role in cognition/behavior!

fMRI时间分辨率较慢，因此引入了EEG和ERPs来解决**问题4：How fast are faces detected and recognized?**，EEG能够提供快速的时间分辨率，但空间分辨率较差。

### Event-Related Potentials (ERPs)
- Face detection: ERP信号表明，在刺激呈现后170毫秒，大脑就开始对面孔产生特定的反应.
- Face recognition: don’t yet know
### Magnetoencephalography (MEG)
- MEG primarily “sees” activity in brain’s folds (sulci), not bumps (gyri).

### Intracranial recording 颅内记录
- 同时具有high spatial and temporal resolution
- Invasive
- 无法确定测量的活动是否在认知/行为中起因果作用。

为研究region X的作用，需要disrupt X，进而引入研究脑损伤患者的方法，用于解答**问题5：What is the causal role of each brain region in face recognition?**

### Patients with focal brain damage
- 患者missing FFA，能recognize objects但不能recognize faces。
- 因此FFA is causally involved in face perception apparently not object perception

**问题6：How is face recognition implement in individual neurons/circuits?**

### Transcranial magnetic stimulation (TMS) 经颅磁刺激
- TMS induces a brief, strong, transient magnetic field over scalp. The only method that can disrupt specific brain regions in normal brains 唯一可以在正常人身上进行的非侵入式干扰方法。
- 可以直接探讨因果作用而不仅仅是相关性
- 空间分辨率低，机制不明确，只能作用于头皮表面的皮层，无法到达FFA
### Electrical stimulation of the brain

# Lecture 6: Experimental Design
Multifactor Experiments main effects and interactions
- **Hypothesis**: The key idea you are testing in the experiment.
- **Prediction**: The precise finding in your data that should be found if the hypothesis is true.
- **Confound 混淆变量**: A difference between your conditions other than the one you are trying to manipulate, that hence provides an alternative account of your data.
- **Contrast**: an activation is generally based on a contrast of two conditions, e.g. finding voxels that respond faces > objects. The point of a contrast is to isolate a mental process

### 对比条件：Minimal Pairs
- fMRI只能显示差异而不能显示 absolute amounts，研究某个 memtal function 需要针对其进行 turn on/off 设计对比试验
- Minimal Pairs differ only in that single mental process and not in anything else.
### 对比条件：Confounds
- If all snake pix have grassy backgrounds, and all nonsnake conditions do not. This thing I thought was a snake-selective brain region is really just responding to grass.
### Decisions toward an Actual Experiment 实验决策

**1. 实验中要运行的具体条件是什么？**
- 设计“**最小对照（Minimal Pairs）**”，只改变一个心理过程。
- 这是实验设计的核心，避免在实验条件中引入多个变量。

**2. 受试者在扫描仪中需要完成什么任务？**
- 对于视觉实验，通常使用**被动观看（Passive Viewing）**或**1-back任务**。
- 不要为不同的刺激设计不同的任务，以避免引入**混淆变量（confounds）**。

**3. 是否有“基线（Baseline）”条件？为什么？**
- 对于视觉实验，常见的基线条件是让受试者盯着一个十字架（没有眼动）。
- 基线条件有助于提供一个**最小视觉处理（minimal visual processing）**的参考，帮助测量大脑对刺激的选择性反应。
- 没有完美的基线，但需要有基线来测量**选择性反应**。

**4. 实验中是否会分配不同条件给不同的受试者，还是让每个受试者完成所有条件？**
- 尽量在同一受试者内进行所有条件的测试，以避免受试者差异影响实验结果。
- 只有在某些情况下无法实现完全的受试者内设计时，才考虑使用其他设计。

**5. 设置多少个“跑次（runs）”，每个跑次中会包含哪些条件？**
- 如果可能，尽量在每个跑次中包含所有条件，以减少跑次间的差异对实验结果的影响。

**6. 如果每个跑次包含多个条件，是集中（clumped）呈现，还是交替（interleaved）呈现？**

**7. 刺激的呈现速率是多少？**

**8. 刺激/条件的顺序如何安排？**
- 避免引入习惯化或疲劳效应。

**9. 数据的分析方法如何确定？**

- 每个受试者个体定义的 Functional Regions of Interest (fROIs)
- 通过 localizer scan 找到每个个体的特定功能性区域
- Standard Designs: Main Effects vs Interactions

<img src="https://github.com/Sihan0229/LectureNotes/blob/main/image/The-Human-Brain-9.13/Main%20Effects%20vs%20Interactions.png?raw=true" width="100%">

# Lecture 7: Category Selectivity, Controversies, and MVPA
- 问题：特定区域（如FFA）是只对某一类别有反应，对其他类别没有反应，还是只是反应的程度不一样？

- 方案：对研究FFA区域对 chairs 和 cars 的反应，如果 $r(\text{Within}) > r(\text{Between})$ ，说明该区域能够区分 chairs 和 cars。

### Neural Decoding with fMRI 神经解码
- 方法：
  - Magnetoencephalography (MEG) 
  - Monkey Neurophysiology: Neural Population Decoding 神经群体解码，通过记录猴子大脑中的神经元的放电率来获取神经活动信息
  - fMRI: 通过监测大脑的 BOLD 响应来获取信息。可以在大脑多个体素（voxels）之间分析信号模式：多体素模式分析（MVPA）

- 解码：Haxby-style correlations, Machine Learning
- 效果对比：**Monkey Neurophysiology** 能够从神经元群体中解码出面孔的身份，而**Monkey fMRI**不能。但是MVPA方法可以用于研究大脑识别的是具体的模板（特定角度、颜色鞋子的图像）还是抽象的表示（某一物体的概念）。

# Lecture 8-9: Navigation

### The Fundamental Problems of Navigation
- Where am I?
  - Familiar location (RSC)
  - unfamiliar location (PPA & OPA)
  - geometry of current location (PPA & OPA)
- How do I get from here (A) to there (B)?
  - Beaconing
  - a mental map (Hippocampus, place cells)
  - current heading w/ respect to that map (RSC, HD cells, OPA, PPA, etc)
  - routes? (boundary cells)
  - reorientation (RSC?/HD cells)

### Parahippocampal Place Area (PPA)
- a region selectively responsive to scenes

**研究内容：**
1. which of these things are driving the response of PPA?
- 对比：Scene, Furniture, Empty Rooms，其中（Scene = Furniture + Empty Rooms）
- spatial layout: Furniture < Empty Rooms

2. Is the PPA involved in the recognition of a particular scene, or in processes specific to familiar scenes?
- 对比MIT与Tufts学生中对MIT与Tuft场景的反应 
- 结论：The PPA does not do anything that requires knowing the specific place 熟悉与不熟悉场景之间没有区别。

**三个结论：** The PPA analyzes the shape of the local environment.
- There is region of parahippocampal cortex that responds
more to scenes than objects.
- When all the objects are removed from the scenes, the
response is unchanged.
- The PPA responds similarly to familiar & unfamiliar scenes

**问题：** 如何说明PPA是对场景有响应，而不是对直线性有响应？

<img src="https://github.com/Sihan0229/LectureNotes/blob/main/image/The-Human-Brain-9.13/PPA%20rectilinearity.png?raw=true" width="100%">

Electrical stimulation of the PPA (place-selectivity
verified by fMRI and iEEG), induced a topographic visual
hallucination: The patient described seeing indoor and outdoor scenes
that included views of the neighborhood he lives in. By
contrast, stimulating the more lateral aspect of the basal
temporal lobe caused distortion of the patient’s
perception of faces.

PPA仅仅是导航系统的一部分
### PPA, Restrospelenial Cortex(RSC), TOS/OPA, Hippocampus
- **PPA（后颞皮层）**：主要负责处理与场景相关的信息，特别是感知和识别场景。

- **RSC（回顾皮层）**：RSC显示出较强的熟悉度效应，在处理熟悉的场景时表现得尤为突出。RSC损伤的患者能够识别建筑物和景观，从而知道自己身处何地，但无法从已知地标获取其他地方的方向信息。

- **TOS（大脑顶叶视觉皮层，又称OPA，场景选择性区域）**：TOS/OPA主要与场景感知相关，但不涉及面孔感知。当OPA区域被干扰时，会影响场景的辨别能力，但不会影响面孔的辨别能力。

- **海马体**：在认知地图（cognitive map）的建立中起到核心作用，帮助我们在空间中导航，记住并定位我们所在的环境。

**PPA & OPA/TOS** 两个区域主要帮助感知和理解场景的空间布局，尤其是与场景的空间结构相关的信息。
**RSC** 主要帮助我们识别熟悉的地方，并且根据认知地图确定自己的位置和方向。
**海马体**负责处理和存储我们的认知地图，使我们能够在环境中定位和导航
### Event-Related fMRI Adaptation 事件相关fMRI适应
- 大脑某一特定区域的神经群体是否能够区分两个不同的刺激?

   e.g. FFA的神经群体是否能够区分两张不同面孔？

   通过测量大脑区域在相同和不同刺激条件下的fMRI反应，能够揭示大脑将什么视为“相同”，什么视为“不同”。

### Head Direction Cells
- 在海马旁回（subiculum）（海马体的一部分）以及其他多个大脑区域中被发现。能够反映动物头部的朝向，帮助大脑感知空间方向。
- 头向细胞的 **放电率（spikes/s）** 与动物头部朝向（0°到360°）有关，当头部朝向特定方向时，头向细胞的放电率会显著增加，当头部朝向某个特定角度（如180°）时，细胞的放电率达到最高值。
- 每个头向细胞对特定方向有最强的反应。多个头向细胞的集群可以共同表示从0°到360°的整个方向范围，通过多个头向细胞的协同工作，大脑能够准确地感知整个360°的方向。

### Grid Cells
- 位于内嗅皮层（Entorhinal Cortex）
- 支持度量距离的编码，帮助动物在环境中移动时感知自己的位置。
- 它们在路径积分（PathIntegration）或dead reckoning（推算当前位置）中尤为重要。这些细胞通过与其他细胞（如头向细胞（HDcells））共同工作，帮助动物计算出位移向量，从而推算出自己在空间中的当前位置。 

**位置细胞**帮助大脑知道我们在哪里，**方向细胞**帮助大脑知道我们的方向，而**网格细胞**则帮助计算位移，并在空间中提供精确的位置信息。

### Border Cells
- 帮助大脑感知我们在环境中的位置，特别是相对于导航障碍物的位置。
- 关注的是周围环境的形状，并且对空间的边界有特殊的反应。

### Reorientation 重定方向

**Geometric Module**
- 仅使用空间布局来确定动物或婴儿在环境中的位置，忽略了颜色、气味等其他感官信息。
- 这种信息封装（Informational Encapsulation）意味着，尽管颜色或气味信息在环境中可用，但大脑的定位系统并不会使用它们，而是专注于几何形状。
- 主要用于判断朝向而非位置。

**Place Cells**
- 地方细胞的方向信息并不完全依赖于外部特征，而是基于动物的位置和方向。

海马体（hippocampus）如何不仅用于空间定位，还涉及时间、社交关系以及思维过程的表示。
- 空间导航：记忆和定位空间信息。
- 时间和空间的结合：存储大范围的记忆，不仅包括空间信息，还包括时间信息。
- 社交认知：参与社交空间的表示，帮助理解社会关系和互动。
- 决策过程：在决策过程中不仅代表位置，还帮助动物**思考**并做出行动选择。

# Lecture 10-11: Development, Nature & Nurture
### Basics of Brain Development
- At birth: 
   - Most neurons
   - Most long-range structural connections

- During first 1-2 yrs:
   - doubles in volume
   - Cortical thickness & surface area increase sharply
   - Complexity of neurons and number of synapses increase greatly
   - Myelination begins before birth, and continues rapidly in first few years, then more slowly through adolescence


Three Test Cases of behavioral and neural development: 
### Face perception and the FFA 

初始状态 + 随时间变化+ 因果关系

- **理论 A**：先天仅具备简单的 “precursor”，只有吸引注意力的初始信号，让婴儿优先关注脸，但具体的面部识别、区分等能力需要通过后天经验逐步学习获得。
- **理论 B**：出生时已具备接近成人的面部感知系统，有完整的面部表征结构，只需轻微 “调整”，不需要大幅学习。

**实验 1：新生儿是否优先关注并检测面部？**
（Johnson et al., 1991；Goren et al., 1975）

- 实验设计：测试出生 1 小时内的新生儿，观察他们对类脸图案和非脸图案的注视时间。
- 结果：新生儿会更久地注视类脸图案，且这种偏好仅在出生后前 2 个月明显。
- 结论：新生儿先天就对 face 有偏好性注意，支持 “理论 A” 中的 “先天前体机制”，存在一个简单的先天模板，能优先抓取面部信息，为后续学习打基础。

**实验 2：新生儿能否区分不同的脸？如何判断他们 “看到了什么”？**（基于 Kellman & Spelke, 1983 的 “习惯化 - 去习惯化” 方法）

- 实验逻辑：婴儿对熟悉的事物注视时间会逐渐变短，对新事物则会多看。通过这个规律，可以判断婴儿能否区分不同的脸。
- 具体应用：给新生儿反复看同一张脸，直到他们注视时间变短；再换另一张脸，若注视时间变长，说明他们能区分。
- 结果：1-3 天大的新生儿能区分不同人的脸，甚至能跨视角（如正面、侧面）识别同一张脸。
- 结论：新生儿不仅能 “看到” 脸，还能区分个体身份，说明先天基础不止于 “检测”，还有初步的 “识别” 能力，但这种能力是否接近成人（理论 B）还需进一步验证。

**实验 3：新生儿是否具备 “整体面部加工” 能力？**（Turati et al., 2006）

- **整体面部加工**是成人面部感知的核心特征，会把脸当作一个整体，而非孤立的眼睛、鼻子来识别，脸倒过来后识别更难，因为破坏了整体结构，即 “倒置效应”。

- 实验设计：给 1-3 天大的新生儿看三种面部刺激：①完整的脸；②仅内部特征（眼睛、鼻子、嘴巴）；③仅外部特征（脸型、头发）。同时测试 “正脸” 和 “倒脸” 两种情况，观察他们能否识别。
- 结果：正脸时，新生儿能通过 “完整脸”“仅内部特征”“仅外部特征” 三种线索识别不同的脸；倒脸时，只能通过 “完整脸” 和 “仅外部特征” 识别，无法通过 “仅内部特征” 识别。
- 结论：新生儿存在 “倒置效应”，说明他们已具备初步的 “整体加工” 能力。这表明先天基础不仅有 “模板”，还有简单的整体加工机制，但能力仍有限，不如成人完善，需要后续学习提升，支持理论 A。那么新生儿是如何进行学习的？

**实验 4：婴儿对 “非人类面孔” 的识别能力如何变化？**（Pascalis et al., 2002）
- 实验设计：测试 6 个月、9 个月大的婴儿和成人，让他们区分 “人类面孔” 和 “猴子面孔”，通过 “偏好注视新面孔” 的时间判断识别能力。
- 结果：6 个月大婴儿：既能区分不同人类的脸，也能区分不同猴子的脸；
9 个月大婴儿和成人：能区分人类的脸，但无法区分猴子的脸。
- 结论：6-12个月之间会发生知觉收窄（perceptual narrowing），即对面孔的感知逐渐专门化；只保留对 “常接触的类别”（如人类脸）的识别能力，对不常接触的（如猴子脸）则逐渐失去区分能力。这类似计算机中 “模型通过训练优化，专注于特定任务” 的过程，说明后天经验（如更多接触人类脸）会 “塑造” 感知系统，支持理论 A 中 “学习机制” 的重要性。

**实验 5：猴子的控制饲养实验：经验是否是面部感知的必要条件？**（Sugita et al., 2008）
- 为验证 “先天基础” 和 “经验” 的作用，研究者通过 “控制饲养” 剥夺猴子接触 “脸” 的经验，观察其面部感知能力是否仍能发展。
- 实验设计：让猴子在出生后 6/12/24 个月内完全看不到任何 “脸”（包括同类的脸、人类的脸），之后首次让它们接触面部刺激，用 “偏好注视法” 测试其能力。
- 结果：首次接触脸时，这些猴子仍会 “优先注视脸”（超过其他新物体）；
能像成年猴子一样准确区分相似的脸；
但后续经验仍有影响：会出现 “感知窄化”（如对不常接触的脸逐渐失去区分能力）。
- 意义：这说明面部感知的核心能力（如检测脸、区分个体）可能不需要 “先天接触脸的经验”，先天就有基础框架，经验的作用更像 “优化” 而非 “塑造核心功能”。这支持了 “先天提供基础，经验微调” 的逻辑，类似计算机中 “初始模型无需特定数据即可运行核心功能，训练数据仅提升精度”。

**Development of Specific Brain Regions**
- Spatial organization （空间结构） is adultlike very early!
- But functional selectivities （功能选择性） are much different.
- Pushes developmental timeline way back.
Importantly constrains role of experience &
maturation. 大脑结构的搭建在非常早期就已经发生，
但具体功能的形成需要进一步经历成熟和经验

**Causal roles of structured experience, and biological maturation central challenge**
- deeply confounded in normal development
- Behavior: Early pattern vision may be important for devel of face system.
- Controlled rearing: **Early face experience not crucial** for face recognition.
- But fMRI: **Face experience is necessary** for development of face patches!

**What if anything is Innate about Face Perception?**
- Bias to look at faces (might be very general template).
- Early visual discrimination abilities (might not be face specific)
- Face patches apparently require experience 

but ... How do they know to always arise right here?
- Pre-existing selectivity?
- Pre-existing connectivity?
### Structural Connectivity from Diffusion Tractography 弥散张量成像
可以通过检测水分子在白质轴突中的受限扩散方向（Restricted Diffusion of Water in Axon Bundles），推断大脑中结构性连接（structural connectivity）。
能很好识别大的纤维束（big fiber bundles），对较小连接的检测能力有限。是目前人类研究连接性的最好工具。

**Do Connectivity Fingerprints Predict Function?**
- 对每一个体素，计算其与全脑各解剖区域的连接强度，形成 connectivity fingerprint, 以此预测该体素的功能。结果发现可以高准确率预测
- All these regions have distinct connectivity fingerprints
- 说明结构连接和功能密切相关
- Recall that most long-range
connectns are present at birth.
### The Visual Word Form Area (VWFA)
**Rewired Ferrets：动物模型实验**

- 在出生时通过手术将来自视网膜的输入引导到本应是听觉皮层（A1）的区域，如果输入决定皮层功能，那么 A1 应该变成 V1（初级视觉皮层）。
- 结果：这个被重定向输入的听觉皮层表现出类似 V1 的功能，因此功能不是天生由位置决定的，而是由连接与经验共同塑造的。
<img src="https://github.com/Sihan0229/LectureNotes/blob/main/image/The-Human-Brain-9.13/Rewired%20Ferrets.png?raw=true" width="100%">

人类读写才发展几千年，不可能进化出先天的阅读脑区。但我们的大脑左半球有一个小区域（VWFA）对字符的 activation 高于线条图画。这说明其完全依赖于后天经验塑造。

**Is the location of VWFA determined by connectivity?**
- yes, we can predict the location of the VWFA at age 8 from connectivity fingerprint at age 5

### Reorientation & The Geometric Module
空间表征系统是先天的吗？（Are Representations of Space Innate?）

老鼠的头向细胞（HD cells） 在出生第12天出现（在睁眼前）；位置细胞（place cells）和边界细胞（border cells）紧随其后。可以推论，空间表征系统基本上是先天的。

动物或婴儿在空间迷失后，会使用空间几何形状而非颜色或气味来重新定向。提出存在一个几何模块（geometric module），专门基于环境几何结构重新定位。

小鸡的几何重定位实验（Controlled Rearing in Chicks）出生前在黑暗中孵化，在矩形或圆形笼中养大。
实验藏起 mom，旋转环境，小鸡再寻找 mom。
小鸡没有接触几何形状经验，但依然能用几何信息成功重新定位，强有力地支持了几何定向模块是先天存在的。

### Controlled Rearing：如何验证系统是否先天？
- 问题：出生时无法直接测试复杂行为，等太晚又会混入经验影响。
- 策略：控制饲养法 (Controlled Rearing) —— 阻止相关经验，看系统是否仍然发展出来。


| 系统   | 先天特征                        | 后天经验作用             |
| ---- | --------------------------- | ------------------ |
| 面孔感知 | 看向脸的偏好（可能是通用模板）             | 真正的“面孔脑区”需要视觉经验形成  |
| VWFA | 无法天生获得（阅读历史太短）              | 由连接模式指导 + 阅读经验驱动发育 |
| 空间系统 | HD cells 出生前即存在，几何定向能力不依赖经验 | 几乎全部是先天建构          |

### 如果大脑在早期受到损伤，或输入极端不同（如先天失明），其功能组织是否仍能保持一致，还是会发生功能重组？
- 可塑性（plasticity）随年龄变化：
成年后语言区受损会导致永久语言障碍；
出生几个月内受损，语言能力发展良好，但可能“迁移”到右半球（RH）；5岁后受损，右半球也无法再承担语言功能。
- FFA在出生时就已定位，病人 Adam 出生当天双侧枕叶-枕颞皮层损伤，尽管物体识别保留，但严重面孔失认。

# Lecture 13: Number: A 'Special' Domain of Mind & Brain?

### Understanding “Approximate Number System” (ANS)

### Brain basis of approx number: Specific regions for number/magnitude?

研究两个“计算失语症”患者（acalculic）

- 病人1：左顶叶损伤 → 近似估算差，减法能力更差
- 病人2：左颞叶损伤 → 近似估算好，但乘法更差

hIPS：近似数量系统的位置
- Simon 等人发现 **顶内沟（hIPS）** 对数字处理反应明显，特异性响应“数字”任务。
- **数字线理论（mental number line）** 反对这个观点，认为：hIPS可能并不特定于“数字”，而是处理任何“量”（magnitude）的区域，例如空间、时间、亮度等。
- Knops et al. (2009)使用 fMRI 和机器学习分类器。训练分类器识别左 vs 右眼动，再用它能够成功预测加法 vs 减法任务。
加法 ≈ 向右注意，减法 ≈ 向左注意，支持了数字和空间共享神经机制的假设。
- Pinel 等人（2004）提出比较数字大小、物体尺寸或亮度的任务，大脑激活区域高度重叠 → 共用“空间编码”，
认知机制上支持“量纲通用（general magnitude system）”的想法。

- Cappelletti 等人（2007）使用 TMS 干扰左侧 IPS，结果发现：数字和点数任务被干扰，但水平/垂直判断不受影响

- 数字在神经元层面的编码：
Nieder 等人训练猴子做数字任务，在顶叶和额叶记录神经元活动。有些神经元专门对某个“数字数量”响应最大，呈钟形调谐曲线。这些数字神经元 abstractly，Over both space & time，且 Over modality
(vis and aud)。

**Summary of Approximate Number System**

- 心智与大脑的近似数字系统（ANS）
与动物、新生儿共享。

- 遵循 **韦伯定律（Weber’s Law）**：区别难度随数字接近程度增加。

- 对物体特征、形态、符号/非符号的抽象
- 巨大个体差异：发育性计算障碍 developmental dyscalculia（IQ正常）
- 儿童ANS能力可以预测以后的数学能力
- hIPS是关键的皮质区域，不仅对于数字大小，而且对于空间/时间/亮度

还未解决的问题：
- hIPS 是数字专属？还是一般“量纲处理器”？
- 数字神经元是否真的“特异”？还是只是对连续变量反应？

Stan Dehaene的观点：
- “大脑将数字视为一种特殊知识类型，有其特定神经机制（如 hIPS）。但对于数字与长度、空间或时间等精细区分而言，hIPS的专属性就会消失。”

- 大脑不是完全均质的白板（anisotropic white paper），也不是清晰划分的模块（modular machine），而是介于两者之间的复杂结构：既有区域专化，也有交叉共享。

# Lecture 15: Hearing and Speech

**Cocktail Party Problem:** 
- ear receives mixture of sources, which add linearly
- BUT:The listener is usually interested in individual sources, which must be inferred from the mixture.
- The problem is ill-posed

**reverberation**
- sound entering ear = sound from source (unknown) * environmental impulse response (unknown)

### Speech	Perception
- **vowels**: see harmonics (parallel horizontal bars) in human voice.
- natural speech: note that vowels are in there but short, punctuated by lots of vertical nonharmonic sounds. (**consonants**). 辅音没有清晰的谐波结构
- 'ba' vs 'pa': diff between VOT (Voice Onset Time), 65ms delay. “pa” 是 送气音，大约延迟 65ms。
- sources of variation: Rate variability, Context variability, Talker variability
- Language-Familiarity Effect (LFE)（语言熟悉度效应）
### The auditory processing pathway
- Primary auditory cortex has tonotopic maps (diff best frequence)

**STRFs 线性时频感受野 linear spectrotemporal filtering**

- Neurons in primary auditory cortex can be thought of as
a bank of linear filters selective for specific frequency
changes over time 将神经元视为一组线性滤波器，每个滤波器对特定时间和频率上的变化敏感。
- 使用模型生成匹配刺激方法验证 STRF 模型的有效性：输入一个自然声音，以及一个经模型匹配合成出的声音（模型预测它们引发的神经响应应当相同）。
结果在fMRI中，模型在初级听觉皮层附近表现很好，但在更高层（非初级区域）预测能力很差。这说明 STRF 模型能解释早期听觉处理，但无法解释高级听觉感知（比如语音或意义）。
- 语音选择性皮层（Speech-Selective Cortex）：fMRI 显示在非初级听觉皮层有一些区域，对语音比对非语音声音反应更强烈。这些区域并不意味着是语言理解 (language-selective) 区域，而是对语音信号本身敏感。
- ECoG脑电记录证实，不同的电极点分别响应语调（intonation）、音素（phonemes）、说话人身份（identity），而不是多个维度的混合响应，说明这些信息是正交/独立编码的（即互不干扰）

# Lecture 16: Music

- Music perception does not engage cortical	regions specialized for language understanding and	vice versa.
- Data-driven fMRI methods discover a strikingly music-specific component in human auditory	cortex.
- The music component does not respond to speech and	vice versa.
- It is present in people who have had no explicit musical training. so not like the VWFA in requirement for explicit instruction (though, maybe like the VWFA in requirement for	experience)
- The music-selective component inferred from fMRI now validated by direct recording from the surface of the brain.
- New neural selectivity for vocal	music discovered.
- These selectivities cannot be accounted for by acoustic properties.

# Lecture 18: Language

### MVPA（多变量模式分析）和RSA（表征相似性分析）神经表征分析方法对比
**MVPA（Multivoxel Pattern Analysis）**
- 问题：某个脑区（ROI）能否区分两类刺激（比如“狗” vs “猫”）？
- 方法：进行二分类，例如训练一个分类器区分不同类别的激活模式，或计算同类内部相关系数 r(within) 是否高于异类之间相关系数 r(between)。
- 局限：binary，只关注能不能区分两个类别。impoverished，必须选两个类来比较。如果加入位置、大小、视角变化等因素，会更好揭示泛化能力，但仍然局限于分类。

**RSA（Representational Similarity Analysis）**
- 核心思想：关心多个刺激条件之间的表征结构（representational space）。
- 方法：把每对条件之间的相似性（通常是神经响应模式之间的相关系数）汇总成一个相似性矩阵（RSA矩阵）。比较两个RSA矩阵的相似性，比如来自两个脑区、两个物种、甚至不同数据模态（行为评分 vs fMRI vs 神经电生理）。
- 优点：不需要做任意二分类，避免主观选择；无需空间配准就能进行跨模态、跨被试、跨物种、跨脑区的比较。
- 关键条件：不同数据集使用相同的刺激材料，这样才能比较矩阵。

### Is language distinct from the rest of thought?
语言和思维是否密不可分？Evidence from brain disorders:
- 重度失语症患者（Global Aphasics）：在Cause-effect reasoning, reorientation, Arithmetic, Algebra, Logic, Theory of Mind等非语言任务中表现正常甚至优异。说明语言不是思维所必须的机制。
- 完全没有语言的人是否还能发展复杂认知？严重听力障碍儿童若在早期缺乏语言暴露，日后对 Theory of Mind 可能受限。说明即使语言不是必须的，它可以影响认知。

Functional Localization 功能定位
- sentences vs non-words 识别哪些大脑区域在处理语言时特别活跃
- 反复验证：是否可靠？
是否能跨任务和呈现方式进行推广？
是否能跨语言推广？
是否能够适应不同材料？（如：听力 vs 阅读）
- 在每个参与者的大脑中定位响应 sentences > non-words 的区域，在新的任务条件下验证这些区域的反应。
- This is different from traditional “group analyses”, where: 
   - Regions are defined anatomically, not functionally 
   - Might fail to detect neural activity
   - Might fail to distinguish between different functional regions

患者研究常常显示语言与思维其他部分是分离的（即语言损伤不必然影响思维），但是fMRI研究却发现语言区域与许多其他认知功能区域存在重叠。
- Hypothesis: If you study individual brains, and localize candidate language regions individually in each subject, the story might be different

### Does the language system itself have distinct components that do different things?
- 目前的研究未发现语言区域有明确的分工，所有的语言区域都参与语法和语义的处理。 
# Lecture 20: Mentalizing and Theory of Mind

### False Belief Paradigm（错误信念范式，FB）
- Sally-Anne task：Sally把球放进篮子里离开了，Anne把球移到盒子里。孩子被问：“Sally 回来后会去哪儿找球？”
- 3岁儿童常常回答“盒子”，5岁儿童通常能正确理解 Sally 的“错误信念”，回答“篮子”。
- 自闭症儿童（ASD）：许多孩子通过FB问题得更晚，甚至永远不能通过。
- Attributing thoughts
### False Photo Stories（错误照片任务，FP）
- FB的对照任务
- 照片拍下相机拍下Sally把球放进篮子里，随后Anne把球移到盒子里。问孩子：照片中球在篮子里还是盒子里？
- 许多自闭症孩子能通过这个任务。

### 使用fMRI研究FB与FP
- fMRI显示大脑对理解FB的反应显著强于对FP的反应。
- **RTPJ（右颞顶联合区）** 能区分FB和FP，Extern, Visceral, Thoughts. Very selective for thinking very selective for thinking
- **MPFC（前额叶内侧皮层）** no difference between conditions, sig.interaction with RTPJ

### Moral Reasoning （道德推理）与 Theory of Mind（理论心智, ToM）的关系
- 意外伤害 vs 故意伤害
- **NT** people agree that accidental harm is more morally permissible than intentional harm. But **ASDs** Less forgiveness for accidental harm.
- 在**正常人群（NTs）**中，对意外伤害的宽恕与rTPJ的激活密切相关，TMS刺激rTPJ后，参与者对于故意伤害的宽容度增加
- rTPJ在理解行为意图和分辨意图与非意图的伤害之间具有关键作用，且这一能力在ASD中被破坏。

# Lecture 21: Brain Networks
# Lecture 24: Attention & Awareness
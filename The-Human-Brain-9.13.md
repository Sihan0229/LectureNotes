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
- **理论 A**：先天仅具备简单的 “precursor”，只有吸引注意力的初始信号，让婴儿优先关注脸，但具体的面部识别、区分等能力需要通过后天经验逐步学习获得。
- **理论 B**：出生时已具备接近成人的面部感知系统，有完整的面部表征结构，只需轻微 “调整”，不需要大幅学习。

**实验 1：新生儿是否优先关注并检测面部？**






### The navigation network and reorientation 

### The Visual Word Form Area

# Lecture 13: Number
# Lecture 15: Hearing and Speech
# Lecture 16: Music
# Lecture 18: Language
# Lecture 20: Mentalizing and Theory of Mind
# Lecture 21: Brain Networks
# Lecture 24: Attention & Awareness
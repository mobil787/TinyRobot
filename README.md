# TinyRobot
TinyRobot summary of TheScience  
[TOC]
# 目录
 - [一级标题](#[M01])

### [M01] Water Strider 机器水黾
https://science.sciencemag.org/content/349/6247/517  
year: 2015
#### Abstract: 
1. 利用superhydrophobic材料依靠水面张力弹跳；  
2. 加热SMA(形状记忆合金)产生形变弹力驱动

![img](./images/01_1.png)  
![img](./images/01_2.png)  

#### abbrev
* SMA: shape memory alloy 形状记忆合金
* SCM: smart composite microstructures
* GFRP: glass fiber reinforced plate
* TRC: torque reversal catapult 转矩逆转弹射器

#### Key notes
* Passive Trigger
  * Experiments were performed on a range of passive trigger specimens to determine the relationship between pulling force and deflection (Fig. S6C).
  * Using the model, we can design the triggering force of the passive trigger when it attains the required deflection for triggering.

* Stiffness of the Sheet SMA Actuator
  * Finally, the stiffness of the actuator, *k*, can be calculated by dividing the triggering force by actuator stroke: ...
  * By varying the design of the passive trigger, various robot prototypes with different actuator stiffnesses were prepared. Table S2 lists their driving forces.

* Motion: **The TRC mechanism**
  * The robot was untethered but **triggered by external heat**. The heating wire (Ni-Cr wire) protruded 1 mm from the free surface, and the actuator was positioned right above the heating wire when the robot was put on the free surface. The actuator was heated by thermal convection around the heating wire until the torque direction reversed.
  * When **heated** above its transition temperature, the actuator’s stiffness changes, inducing a negative strain and pulling the passive trigger in the body structure until the torque direction is reversed (Fig. 3, A to C).
  * A thin **heating wire** was carefully placed just below the robot body to activate the SMA actuator. As the SMA actuator transitions, the force increases, and the passive trigger begins to bend (Fig. 3, A to C).When the actuator passes through the center joint, the torque direction changes, and the body structure folds downward, generating a rapid snap-through.

* Fabrication and Materials
  * The robot structure was designed so that the smart composite microstructures (SCM) manufacturing process could be applied (24).
  * Fabrication of the jumping robotic insect using SCM (Fig. S5).  
  ![img](./images/01_3.png)  
  <!-- <img src="./images/01_3.png" alt="img" style="zoom:20%;" /> -->

---


### [M04] Electrostatic footpads insect-scale soft robots 机器小强软体机器人
https://robotics.sciencemag.org/content/6/55/eabe7906  
year: 2021

#### Abstract:   
1. 通过一定频率的AC电压激励，让可弯曲的单压电薄膜(curved unimorph piezoelectric film)或PVDF伸缩产生前进的动力。
2. 改变（静电）前脚板对地的摩擦力，能够实现转弯。

#### abbrev
* curved unimorph piezoelectric film 可弯曲的单压电薄膜
* light-induced motion adjustment controls 光感运动调整
* SEM: scanning electron microscopy 扫描电子显微镜 
* PVDF: piezoelectric polyvinylidene fluoride 压电聚偏二氟乙烯
* PET: polyethylene terephthalate 聚对苯二甲酸乙二醇酯（树脂材料）
* PI: polyimide 聚酰亚胺（一种高性能工程材料,在高温下具有优异的物理和化学性能,已作为多种材料广泛应用于微电子包装、高温粘合剂及复合材料等）
* COT: cost of transport 单位距离能耗

#### Key Notes
 * 1.conventional rigid-body robots can use **differential gaits** to realize turning motions similar to those in insects (5–10).
 * 2.strategy 
    * In nature, insects having flexible bodies can dynamically tune the friction force with secretions between their feet and the ground to improve locomotion (23–27). Similar schemes have been emulated in small-scale robots to accomplish various exceptional functions, such as climbing on a vertical wall using the electrostatic force for attachments (7, 19).  The friction force between the electrostatic footpads and the ground can be independently adjusted by varying the footpads DC bias voltages to regulate the moving trajectory.
    * Inspired by this strategy, a tethered prototype soft robot has been built by using a **curved unimorph piezoelectric film structure** as the main body for fast moving speeds, and two electrostatic footpads have been implemented for speedy turning motions. The robot is composed of a main body, a rear leg, and two front legs with electrostatic footpads. The front leg is 4 mm in height and is composed of PET/silicone/electrode/ PI. The rear leg is a piece of PET film attached to the tail of the robot’s main body, with a height of 3.5 mm.
    * The electrostatic front footpad has the design shape of a droplet and is made of a polyimide (PI; 5um in thickness) film at the bottom with a Ti/Au (10/100 nm) electrode on the top. The total footpad area is 32 mm2, as shown in Fig. 1C. A PET frame is attached on top of the footpad with the help of silicone adhesive as the mechanical support. The electrodes of the right and left footpads are connected to the bottom and top electrodes of the piezoelectric unimorph robot body, respectively. The droplet-shaped design is helpful to enlarge the contact area between the footpad and the ground surface with little impact on the linear moving speed.
    ![image](https://user-images.githubusercontent.com/26667177/129678114-f1b5deb6-4e39-4b5b-bb2e-1ad4f43d7db1.png)
    
  * 3.Motion  
    * Under the excitation of an AC driving voltage at the structural resonant frequency (113 to 190 Hz for the prototypes with slightly different design and fabrication variations), **the curved piezoelectric unimorph structure can extend and shrink repeatedly to result in the rear leg and the two front legs striking the ground for fast forward movements** (fig. S1).
    ![image](https://user-images.githubusercontent.com/26667177/129679808-aaf42f49-e9df-4e0c-a8a9-0a3ed6f4376e.png)
    * In nature, an ant can change the friction force with the ground by secretion, as shown in Fig. 1D, to help its locomotion on smooth or vertical surfaces (28). The agility of the soft robot can be markedly improved by adding two electrostatic footpads to adjust its friction force (f_shear), as shown in Fig. 1E. By **adjusting the friction force** between the right and left electrostatic footpads, the robot can produce movements with adjustable trajectories, including straight, clockwise, and counterclockwise motions. A high gradient value, which is proportional to the electrostatic adhesion force and inversely proportional to the mass, implies that the robot can easily make a turning motion. As such, a large applied voltage together with a low body mass can increase the agility.
    
    ![image](https://user-images.githubusercontent.com/26667177/129682226-fcffb69e-27fc-44d3-9d22-127450cce31c.png)
    
  * 4.Untethered design
    * An untethered version of the soft robot (2.4 cm by 2.2 cm, 240 mg) together with **a payload of 1.66 g** —including a battery (3.7 V, 40 mAh; HuiXinLi Inc.), two photo sensors (GL3549, JCGL Inc.), and a flexible circuit board. The measured resonance frequency was 410 Hz; Specifically, the circuit can output a 500-Vpp driving voltage to the robot’s main body. 
    * two photoresistors were used to realize the turning function of the robot with an analog control scheme (53) as illustrated in Fig. 5C, with a detailed circuit diagram in fig. S16A.
    
    ![image](https://user-images.githubusercontent.com/26667177/129729155-0fa969a0-ebce-4478-8882-1b28e7f3d543.png)
    ![image](https://user-images.githubusercontent.com/26667177/129729346-66697298-9c1e-4b99-91d5-bce931b2ea2e.png)
    
  * 5.Fabrication   
    * The fabrication processes are given in Materials and Methods on the basis of the previous work (18) with added electrostatic footpads.
    
    ![image](https://user-images.githubusercontent.com/26667177/129730400-57d5ab68-be50-4fa9-917b-d61cc1b22b42.png)


---

### [M05] Soft-bodied adaptive multimodal locomotion strategies in fluid-filled confined spaces 软体机器人目标在人体血管移动
https://advances.sciencemag.org/content/7/27/eabh2022  
year: 2021

#### Abstract:   
1. 磁性软体材料制作，在不同的外部磁场变换下改变形状和运动形态。
2. 主要目的用于人体内血管等充满液体的封闭体腔内运动。

#### abbrev
* 

#### Key Notes
 * Motion  
   * Sheet-Shaped
     * When the robot is in a big gap, where the ratio between the robot length and the gap width is smaller than 2.6 (fig. S2), applying **B** in the x-z plane can deform it into a “C” shape. Its orientation is determined by the direction of **B** (Fig. 1Bi). 
     * When the robot comes into a small gap, where >2.6, applying **B** in the x-z plane no longer produces the C shape, while a sinusoidal shape appears because of the squeezing of the upper and lower boundaries. The positions of the wave crests and troughs are determined by the direction of **B** (Fig. 1Bii). 
     * When the robot navigates into a cylindrical tube, which has an inner diameter larger than the robot width, applying a rotating **B** in the z-y plane can twist it into a helical shape (Fig. 1Biii). By using these shape changes ,the robot can achieve adaptive locomotion in confined spaces with different cross-sectional geometries and sizes (Fig. 1C).  
![image](https://user-images.githubusercontent.com/26667177/129909106-27872bdd-c14f-4102-b419-77cbf6608ede.png)

   * Undulatory crawling locomotion mode  
     By applying a rotating B→ in the x-z plane, the sheet-shaped robot produced traveling waves along the body’s longitudinal direction and achieved two distinct locomotion modes in a small gap filled with viscous fluid (343 cSt). As the experiments show in Fig. 2A and movie S1, a rotating B → with a frequency of 1 Hz resulted in locomotion in the same direction as the traveling body wave of the robot. However, keeping the magnitude and the rotating direction of B→ fixed while increasing the actuation frequency to 10 Hz reversed the robot locomotion direction. When the robot is actuated at different frequencies or placed in different fluid viscosities, it is subjected to different friction and hydrodynamic forces. Thus, the transition between the undulatory swimming and crawling modes is largely dictated by the fluid viscosity and the rotating frequency of **B**.  
![image](https://user-images.githubusercontent.com/26667177/130024543-ff243788-f15b-45dd-b639-149c1d42624a.png)

   * Helical surface crawling locomotion mode  
     When the robot moves inside a fluid-filled cylindrical tube, simply providing a rotating B→ in the x-z plane always fails to produce stable undulatory locomotion. Stable locomotion in a cylindrical tube can be achieved by changing the plane of the rotating B→ from the x-z plane to the y-z plane to twist the flat robot into a helical shape as shown in Fig. 1Biii. After forming the helical shape, the robot can maintain this configuration and rotate along with the rotating B→ .One merit of such helical surface crawling is that the robot body does not block the tube so that the fluid can still pass through ... This feature also endows the robot with the capability to move with or against the fluid flow and allows the robot to anchor to a position to withstand the flow even when B→ is off, which outperforms the undulatory locomotions (fig. S9). The propulsion of the rotating helically shaped robot was achieved because of the anisotropic friction force distribution along the body (Fig. 5C).  
![image](https://user-images.githubusercontent.com/26667177/130025820-115e9855-c90a-4dc2-9bb4-c8543d5c0142.png)


 * Fabrication and Materials
   * To program the sinusoidal magnetization profile along the robot length, the robot was cut from a thin film of the magnetic composite elastomer, wrapped to a nonmagnetic cylindrical rod with the help of water-soluble glue, and lastly magnetized in a 1.8-T uniform magnetic field (Fig. 1A, i to iii).
   * The ferromagnetic neodymium-iron-boron (NdFeB) microparticles tend to align their magnetization directions along with the external magnetic field B→ , inducing torques that deform the soft elastomeric robot body (8, 23). The sheet-shaped robots developed in this study had the same width (1 mm) and thickness (0.24 mm) and similar sinusoidal magnetization profiles with an initial phase shift of 45° (Fig. 1Aiv). The robot lengths were designed to be at least 11 times larger than the robot thickness to achieve large deformations (fig. S1).  
![image](https://user-images.githubusercontent.com/26667177/129904871-fa6ac884-f5f8-40ef-b9dd-5ae688060866.png)

























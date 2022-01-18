==Математическая модель==
Уравнение движение для каждой из материальных точек записывается следующим образом:

<math>
   m\underline{\ddot{x}}_i(t)=\underline{F}_{R_1}+\underline{F}_{R_2}+\underline{F}_{D_1}+\underline{F}_{D_2}+\underline{P}+\underline{F}_{Wall}\\
   \underline{x}_i(0)=\underline{x}_i^0,~\underline{v}_i(0)=v_i^0~~~i=1,\ldots,n
</math>


где 
<math>
   \underline{F}_{R_1}, \underline{F}_{R_2}\\
</math> - силы упругости действующие на <math>i</math>-ую частицу со стороны <math>i-1</math> и <math>i+1</math> соответственно;

<math>
   \underline{F}_{D_1},\underline{F}_{D_2}\\
</math> - силы демпфирования пружины действующие на <math>i</math>-ую частицу со стороны <math>i-1</math> и <math>i+1</math> соответственно;

<math>
  \underline{P}
</math> - давление создаваемое газом;

<math>
 \underline{F}_{Wall}\\
</math> - сила взаимодействия между воздушным шаром и стеной;

Сила упругости, возникающая в пружине соединяющей частицу 1 и 2, вычисляется по следующей формуле:

<math>
   \underline{F}_{R}= -(||\underline{r}_2-\underline{r}_1|| - l_0)k_R
</math>,  где <math>k_R</math> - коэффициент жесткости пружины.

Сила демпфирования:

<math>
   \underline{F}_{D}= (\underline{v}_2-\underline{v}_1)\cdot\frac{\underline{r}_2-\underline{r}_1}{||\underline{r}_2-\underline{r}_1||}k_D
</math>, где <math>k_D</math> - коэффициент демпфирования пружины.

Давление:

<math>
   \underline{P}=\frac{1}{V}l_{12} P \underline{n}
</math>,  где <math> V </math> - актуальный объем шара, <math> l_{12}</math> - актуальная длина пружина, <math> P </math> - модуль давления, <math> \underline{n}</math> - нормаль к пружине, направленная наружу.

Взаимодействие шара со стеной:

<math>
   \underline{F}_{Wall}=-\nabla \Pi(r)
</math>,  где  <math>\Pi(r)=4\varepsilon[(\frac{a}{r})^{12}-(\frac{a}{r})^6]</math>

Интегрирование уравнений движения осуществляется при помощи метода Верле.

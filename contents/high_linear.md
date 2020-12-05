use_math: true 
comments: true

출처 1 : 유튜브 수악중독 (https://www.youtube.com/user/minipole)

출처 2 : 블로그 수악중독 (https://mathjk.tistory.com/)

---

## [평면벡터](https://github.com/juneilsam/munsong_math/blob/main/contents/high_linear.md#%ED%8F%89%EB%A9%B4%EB%B2%A1%ED%84%B0-1)

### [1.벡터의 연산](https://github.com/juneilsam/munsong_math/blob/main/contents/high_linear.md#1벡터의-연산-1)

### [2.평면벡터의 성분과 내적](https://github.com/juneilsam/munsong_math/blob/main/contents/high_linear.md#2평면벡터의-성분과-내적-1)

---

## [공간도형과 공간좌표](https://github.com/juneilsam/munsong_math/blob/main/contents/high_linear.md#공간도형과-공간좌표-1)

### [1.공간도형](https://github.com/juneilsam/munsong_math/blob/main/contents/high_linear.md#1공간도형-1)

### [2.공간좌표](https://github.com/juneilsam/munsong_math/blob/main/contents/high_linear.md#2공간좌표-1)

---

## [공간벡터](https://github.com/juneilsam/munsong_math/blob/main/contents/high_linear.md#공간벡터)

### [1.공간벡터의 성분](https://github.com/juneilsam/munsong_math/blob/main/contents/high_linear.md#1공간벡터의-성분-1)

### [2.공간벡터의 내적](https://github.com/juneilsam/munsong_math/blob/main/contents/high_linear.md#2공간벡터의-내적-1)

### [3.공간에서의 직선의 방정식](https://github.com/juneilsam/munsong_math/blob/main/contents/high_linear.md#3공간에서의-직선의-방정식-1)

### [4.평면의 방정식](https://github.com/juneilsam/munsong_math/blob/main/contents/high_linear.md#4평면의-방정식-1)

### [5.점과 평면 사이의 거리](https://github.com/juneilsam/munsong_math/blob/main/contents/high_linear.md#5점과-평면-사이의-거리-1)


---

## 평면벡터

### 1.벡터의 연산
(1) 벡터의 뜻

\- 다음 두 요소를 가지는 양

    - 크기
    - 방향
    
</br>
(2) 벡터의 표시

\- 점 A에서 점 B로 향하는 화살표를 사용하여 크기와 방향을 나타낸다.

\- <a href="https://www.codecogs.com/eqnedit.php?latex=\overrightarrow{AB}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\overrightarrow{AB}" title="\overrightarrow{AB}" /></a> 또는 <a href="https://www.codecogs.com/eqnedit.php?latex=\overrightarrow{a}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /></a>

    - 점 A : 벡터 AB의 시점

    - 점 B : 벡터 AB의 종점

</br>
(3) 벡터의 크기


: 선분 AB의 길이


\- <img src="https://latex.codecogs.com/svg.latex?\tiny&space;{\left&space;|\overrightarrow{AB}&space;\right&space;|}" title="\tiny {\left |\overrightarrow{AB} \right |}" /> 또는 <img src="https://latex.codecogs.com/svg.latex?{\left&space;|\overrightarrow{a}&space;\right&space;|}" title="{\left |\overrightarrow{a} \right |}" />


\- 단위 벡터 : 크기가 1인 벡터


\- 영벡터

    - AA, BB와 같이 시점과 종점이 일치하는 벡터

    - 기호와 함께 0으로 표시
   
    - 임의의 방향(고등학교에서는 방향을 생각하지 않는다고 한다)
</br>
※ 평면벡터 : 평면에서의 벡터
</br>
</br>
</br>
(4) 서로 같은 벡터

  \- 위치에 관계없이 크기와 방향이 같다면 모두 같은 벡터이다.

  \- 선분을 평행이동하여 같은 벡터와 겹칠 수 있다.

  \- 방향이 반대인 벡터
: <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{AB}" title="\tiny \overrightarrow{AB}" /> = -<img src="https://latex.codecogs.com/svg.latex?\overrightarrow{BA}" title="\overrightarrow{BA}" />

: <img src="https://latex.codecogs.com/svg.latex?\left&space;|&space;\overrightarrow{a}&space;\right&space;|" title="\left | \overrightarrow{a} \right |" /> = <img src="https://latex.codecogs.com/svg.latex?\small&space;\left&space;|&space;\overrightarrow{-a}&space;\right&space;|" title="\small \left | \overrightarrow{-a} \right |" />
</br>
</br>
</br>
(5)벡터의 덧셈과 뺄셈

1)벡터의 덧셈

\- <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}&space;=&space;\overrightarrow{AB},&space;\overrightarrow{b}&space;=&space;\overrightarrow{BC}" title="\overrightarrow{a} = \overrightarrow{AB}, \overrightarrow{b} = \overrightarrow{BC}" />일 때,

\: <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> + <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" /> = <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{AB}" title="\overrightarrow{AB}" /> + <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{BC}" title="\overrightarrow{BC}" /> = <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{AC}" title="\overrightarrow{AC}" />

\- 삼각형 법 : 벡터 1과 벡터 2의 종점과 시점을 일치시킨다(벡터 1의 시점과 벡터 2의 종점을 이은 벡터가 합).

\- 평행사변형 법 : 벡터 1과 벡터 2의 시점을 일치시키고, 평행사변형을 만든다(시점으로부터 대각선에 위치한 벡터가 합).

\- 벡터의 덧셈에 대한 연산법칙

    - 교환법칙
    
    - 결합법칙
</br>
</br>
2) 벡터의 뺄셈
</br>

: <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> - <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" /> = <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> + (-<img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" />)

</br>
</br>
(6) 벡터의 실수배

\- 실수 k와 <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" />에 대하여

: <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> ≠ <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{0}" title="\overrightarrow{0}" />일 때,

  ① k > 0이면, k<img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" />는 <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" />와 같은 방향이고 크기는 k|<img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" />|인 벡터
  
  ② k = 0이면, k<img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> = <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{0}" title="\overrightarrow{0}" />
  
  ③ k < 0이면, k<img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" />는 <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" />와 반대 방향이고 크기는 |k||<img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" />|인 벡터
  
: <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> = <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{0}" title="\overrightarrow{0}" />일 때, k<img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> = <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{0}" title="\overrightarrow{0}" />

\- 벡터의 실수배에 대한 연산법칙

    - 결합법칙
    
    - 분배법칙
<br/>    
<br/>    
(7) 벡터의 평행

\- 벡터의 평행

    : 영벡터가 아닌 두 벡터의 방향이 같거나 반대일 때, 두 벡터가 서로 평행하다고 하며, 이것을 기호로 //와 같이 나타낸다.
    
\- 두 벡터가 평행할 조건

    : 영벡터가 아닌 두 벡터에 대하여, a // b ⇔ b = ka (k는 0이 아닌 실수)
    
<br/>

### 2.평면벡터의 성분과 내적

(1) 위치벡터

: 평면에서 한 정점 O를 시점으로 하는 벡터

    - 일반적인 좌표평면에서 위치벡터의 시점 : 원점 O

    - 두 위치벡터가 서로 같으면 : 두 위치벡터의 종점이 동일

    - 두 위치벡터의 종점이 같으면 : 두 위치벡터는 서로 같은 벡터

<br/>

(2) 평면벡터의 성분

: 위치벡터 a의 종점의 좌표가 (a₁, a₂)일 때,

    a₁, a₂가 벡터 a의 성분
    
※ 단위벡터 : x축, y축의 양의 방향과 같고, 크기가 1인 단위벡터

<br/>

(3) 두 평면벡터가 서로 같을 조건

\- 두 점 A = (a₁, a₂), B = (b₁, b₂)에 대하여, 각 위치벡터(a, b)가 서로 같은 벡터가 되기 위해서는 그 종점의 좌표가 같아야 한다.

    a = b ⇔ a₁ = b₁, a₂ = b₂
    
<br/>

(4) 평면벡터의 크기

\- 벡터a = (a₁, a₂)일 때, 

  : <img src="https://latex.codecogs.com/svg.latex?\left&space;|\overrightarrow{a}&space;\right&space;|" title="\left |\overrightarrow{a} \right |" /> = <img src="https://latex.codecogs.com/svg.latex?\sqrt{{a_1}^{2}&space;&plus;&space;{a_2}^{2}}" title="\sqrt{{a_1}^{2} + {a_2}^{2}}" />

<br/>

(5) 평면벡터의 성분에 의한 연산

\- 두 평면벡터 a = (a₁, a₂), b = (b₁, b₂)

    - a + b = (a₁ + b₁, a₂ + b₂)
    
    - a - b = (a₁ - b₁, a₂ - b₂)

    - ka = (ka₁, ka₂)
    
<br/>

(6) 평면벡터의 성분과 크기

\- 두 점 A(a₁, a₂), B(b₁, b₂)

   1) <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{AB}" title="\overrightarrow{AB}" /> = (b₁ - a₁, b₂ - a₂)
    
   2) <img src="https://latex.codecogs.com/svg.latex?\left&space;|&space;\overrightarrow{AB}&space;\right&space;|" title="\left | \overrightarrow{AB} \right |" /> = <img src="https://latex.codecogs.com/svg.latex?\sqrt{(b_{1}&space;-&space;a_{1})^{2}&space;&plus;&space;(b_{2}&space;-&space;a_{2})^{2}}" title="\sqrt{(b_{1} - a_{1})^{2} + (b_{2} - a_{2})^{2}}" />
 
 <br/>
   
(7) 평면벡터의 내적

\- 벡터 a = (a₁, a₂), b = (b₁, b₂)

  : a ˙ b = a₁b₁ + a₂b₂


\- 평면벡터의 내적의 성질

    - 교환법칙
    
    - 분배법칙
    
    - 결합법칙
    
    
\- 평면벡터의 수직 조건과 평행 조건


\- 영벡터가 아닌 두 공간벡터 <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" />, <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" />에 대하여
  
   - 수직 조건 : <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> · <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" /> = 0
   - 평행 조건 : <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> · <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" /> = ± |<img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" />|| <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" />|
   
<br/>   

(8) 방향벡터를 이용한 직선의 방정식

\- 점 A(x₁, y₁)을 지나고 방향벡터가 <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{u}" title="\overrightarrow{u}" /> = (u₁, u₂)인 직선의 방정식은

  : <img src="https://latex.codecogs.com/svg.latex?\frac{x&space;-&space;x_{1}}{u_{1}}&space;=&space;\frac{y&space;-&space;y_{1}}{u_{2}}" title="\frac{x - x_{1}}{u_{1}} = \frac{y - y_{1}}{u_{2}}" /> (단, u₁u₂ ≠ 0)
  
  ※ 방향벡터 : 직선에 평행한, 영벡터가 아닌 벡터
  
<br/>  
  
(9) 법선벡터를 이용한 직선의 방정식

\- 점 A(x₁, y₁)을 지나고 법선벡터가 <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{n}" title="\overrightarrow{n}" /> = (n₁, n₂)인 직선의 방정식은

  : n₁(x - x₁) + n₂(y - y₁) = 0
  
  ※ 법선벡터 : 직선에 수직인, 영벡터가 아닌 벡터

<br/>
<br/>
<br/>

---

## 공간도형과 공간좌표

### 1.공간도형
(1)직선, 평면의 위치 관계

\- 평면의 결정조건

    - 한 직선 위에 있지 않은 서로 다른 세 점
    - 한 직선과 그 직선 위에 있지 않은 한 점
    - 한 점에서 만나는 두 직선
    - 평행한 두 직선


    ※ 평면에서와 같이 공간에서도 서로 다른 두 점을 지나는 직선은 오직 하나.
    ※ 공간에서 한 점에서 만나는 두 직선은 한 평면을 결정하고 평행한 두 직선도 한 평면을 결정한다.
    
<br/>
    
\- 공간에서 두 직선의 위치 관계

    - 한 평면 위에 있다.
  
      : 만난다.
    
      : 평행하다.
    
    - 한 평면 위에 있지 않다.
  
      : 꼬인 위치에 있다.
    
<br/>    
    
\- 직선과 평면의 위치 관계

    - 만난다.
    
      : 포함된다(두 점 이상을 공유하면 직선 위의 모든 점은 평면 위에 있다).
    
      : 한 점에서 만난다.
    
    - 만나지 않는다.
  
      : 평행하다(직선과 평면이 공유점을 가지지 않는다, //).
    
<br/>    
    
\- 평면과 평면의 위치 

    - 만난다.
    
      : 서로 다른 두 평면이 한 점을 공유하면, 두 평면은 그 점을 지나는 한 직선을 공유한다(교선).
    
    - 만나지 않는다.
  
      : 평행하다. //
    
    - 일치한다.
  
<br/>

\- 직선, 평면의 평행에 대한 성질

    - 평행한 두 평면 α, β가 다른 평면 γ와 만나서 생기는 교선을 각각 l, m이라고 할 때
  
    l과 m은 서로 평행하다.
    
    
    - 두 평면 α와 β가 평행하면
  
    평면 α에 포함되는 직선은 평면 β와 평행하다.
    
    
    - 두 직선 l과 m이 평행할 때, 직선 l을 포함하는 평면 α가 직선 m을 포함하지 않으면
  
    직선 m과 평면 α는 평행하다.
    
    
    - 직선 l과 평면 α가 평행할 때, 직선 l을 포함하는 평면 β와 평면 α가 교선 m을 가지면
  
    두 직선 l, m은 서로 평행하다.
    
    
    - 평면 α 위에 있지 않은 점 P를 지나고 평면 α에 평행한 서로 다른 두 직선 l, m에 의하여 결정되는
  
    평면 β는 평면 α와 평행하다.
    
  <br/>
  
\- 직선과 평면의 수직

     : 직선이 평면 위의 모든 직선과 수직일 때, 그 직선과 평면은 수직이라고 한다.
  
<br/>
<br/>

(2) 삼수선 정리

    평면 α 위에 있지 않은 점 P, α 위의 점 O, 점 O를 지나지 않는 α 위의 직선 l, 직선 l의 점 H
  
\- <img src="https://latex.codecogs.com/svg.latex?\overline{PO}" title="\overline{PO}" /> ⊥ α,  <img src="https://latex.codecogs.com/svg.latex?\overline{OH}" title="\overline{OH}" /> ⊥ l이면 <img src="https://latex.codecogs.com/svg.latex?\overline{PH}" title="\overline{PH}" /> ⊥ l

\- <img src="https://latex.codecogs.com/svg.latex?\overline{PO}" title="\overline{PO}" /> ⊥ α,  <img src="https://latex.codecogs.com/svg.latex?\overline{PH}" title="\overline{PH}" /> ⊥ l이면 <img src="https://latex.codecogs.com/svg.latex?\overline{OH}" title="\overline{OH}" /> ⊥ l

\- <img src="https://latex.codecogs.com/svg.latex?\overline{PH}" title="\overline{PH}" /> ⊥ l,  <img src="https://latex.codecogs.com/svg.latex?\overline{OH}" title="\overline{OH}" /> ⊥ l,  <img src="https://latex.codecogs.com/svg.latex?\overline{PO}" title="\overline{PO}" /> ⊥ <img src="https://latex.codecogs.com/svg.latex?\overline{OH}" title="\overline{OH}" />이면  <img src="https://latex.codecogs.com/svg.latex?\overline{PO}" title="\overline{PO}" /> ⊥ α

<br/>

(3) 정사영
: 평면 위에 있지 않은 한 점에서 평면에 내린 수선의 발

<br/>

### 2.공간좌표


(1) 공간에서 점의 좌표


    - 좌표축 : 공간의 한 점에서 서로 직교하는 세 수직선을 그었을 때, 각각의 수직선(x축, y축, z축)

    - 좌표평면 : 좌표축 2쌍에 의하여 결정되는 평면(xy평면, yz평면, zx평면)

    - 공간좌표 : 공간에 있는 임의의 한 점에 대하여 각 좌표평면이 나머지 좌표축과 만나는 점으로 이루어진 세 실수의 순서쌍 (a, b, c)

    - 좌표공간 : 공간에 있는 임의의 한 점의 좌표가 주어진 공간 (P(a, b, c))

※ 좌표평면은 나머지 한 좌표축 = 0에서 수직으로 만나므로, 해당 평면 위의 모든 점의 나머지 한 좌표축의 좌표는 0이다.

<br/>

(2) 좌표공간에서 두 점 사이의 거리

\- 좌표공간의 두 점 P(x₁, y₁, z₁)과 Q(x₂, y₂, z₂) 사이의 거리는

   : <img src="https://latex.codecogs.com/svg.latex?\overline{PQ}&space;=&space;\sqrt{\left&space;(&space;x_{2}&space;-&space;x_{1}&space;\right&space;)^{2}&space;&plus;&space;\left&space;(y_{2}&space;-&space;y_{1}&space;\right&space;)^{2}&space;&plus;&space;\left&space;(z_{2}&space;-&space;z_{1}&space;\right&space;)^{2}}" title="\overline{PQ} = \sqrt{\left ( {x_2} - {x_1} \right )^{2} + \left ({y_2} - {y_1} \right )^{2} + \left ({z_2} - {z_1} \right )^{2}}" />


\- 원점 O와 점 P(x₁, y₁, z₁) 사이의 거리는

   : <img src="https://latex.codecogs.com/svg.latex?\overline{OP}&space;=&space;\sqrt{&space;{x_1}^{2}&space;&plus;&space;{y_1}^{2}&space;&plus;&space;{z_1}^{2}}" title="\overline{OP} = \sqrt{ {x_1}^{2} + {y_1}^{2} + {z_1}^{2}}" />

<br/>
<br/>
<br/>

---

## 공간벡터

### 1.공간벡터의 성분

(1) 공간벡터

: 공간에서의 벡터

<br/>
   
(2) 공간벡터의 성분

: <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}&space;=&space;\overrightarrow{OA}" title="\overrightarrow{a} = \overrightarrow{OA}" />는 <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> = (a₁, a₂, a₃)과 같이 나타낸다.
   
: a₁, a₂, a₃가 벡터 <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" />의 성분.
   
    a₁ = x성분    a₂ = y성분    a₃ = z성분

<br/>

※ 두 공간벡터 <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> = (a₁, a₂, a₃), <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" /> = (b₁, b₂, b₃)에 대하여

  - <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> = <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" /> ⇔ a₁ = b₁, a₂ = b₂, a₃ = b₃
  
  - <img src="https://latex.codecogs.com/svg.latex?\left&space;|&space;\overrightarrow{a}&space;\right&space;|" title="\left | \overrightarrow{a} \right |" /> = <img src="https://latex.codecogs.com/svg.latex?\sqrt{{a_{1}}^{2}&space;&plus;&space;{a_{2}}^{2}&space;&plus;&space;{a_{3}}^{2}}" title="\sqrt{{a_{1}}^{2} + {a_{2}}^{2} + {a_{3}}^{2}}" />
  
<br/>
  
(3) 공간벡터의 성분에 의한 연산
  
\- 두 공간벡터 <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> = (a₁, a₂, a₃), <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" /> = (b₁, b₂, b₃)에 대하여

- <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> + <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" /> = (a₁ + b₁, a₂ + b₂, a₃ + b₃)

- <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> - <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" /> = (a₁ - b₁, a₂ - b₂, a₃ - b₃)

- k<img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> = (ka₁, ka₂, ka₃) (단, k는 실수)

<br/>

※ 좌표공간의 두 점 A(a₁, a₂, a₃), B(b₁, b₂, b₃)에 대하여

  - <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{AB}" title="\overrightarrow{AB}" /> = (b₁ - a₁, b₂ - a₂ , b₃ - a₃)
  
  - <img src="https://latex.codecogs.com/svg.latex?\left&space;|&space;\overrightarrow{AB}&space;\right&space;|" title="\left | \overrightarrow{AB} \right |" /> = <img src="https://latex.codecogs.com/svg.latex?\sqrt{({b_{1}&space;-&space;a_{1}})^{2}&space;&plus;&space;({b_{2}&space;-&space;a_{2}})^{2}&space;&plus;&space;({b_{3}&space;-&space;a_{3}})^{2}}" title="\sqrt{({b_{1} - a_{1}})^{2} + ({b_{2} - a_{2}})^{2} + ({b_{3} - a_{3}})^{2}}" />

<br/>

### 2.공간벡터의 내적

\- 영벡터가 아닌 두 공간벡터 <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> = (a₁, a₂, a₃), <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" /> = (b₁, b₂, b₃)

  : <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> · <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" /> = a₁b₁ + a₂b₂ + a₃b₃
  
  
  : 두 공간벡터 둘 중 하나가 영벡터일 경우에는 <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> · <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" /> = 0으로 정한다.
  
\- 내적의 연산법칙

    - 교환법칙
    
    - 결합법칙
    
    - 분배법칙
    
\- 영벡터가 아닌 두 공간벡터 <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" />, <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" />에 대하여
  
   - 수직 조건 : <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> · <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" /> = 0
   - 평행 조건 : <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" /> · <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" /> = ± |<img src="https://latex.codecogs.com/svg.latex?\overrightarrow{a}" title="\overrightarrow{a}" />|| <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{b}" title="\overrightarrow{b}" />|
   
<br/>

### 3.공간에서의 직선의 방정식

\- 점 A(x₁, y₁, z₁)를 지나고 방향벡터 <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{u}" title="\overrightarrow{u}" /> = (u₁, u₂, u₃)인 직선의 방정식

  : <img src="https://latex.codecogs.com/svg.latex?\frac{x&space;-&space;x_{1}}{u_{1}}&space;=&space;\frac{y&space;-&space;y_{1}}{u_{2}}&space;=&space;\frac{z&space;-&space;z_{1}}{u_{3}}" title="\frac{x - x_{1}}{u_{1}} = \frac{y - y_{1}}{u_{2}} = \frac{z - z_{1}}{u_{3}}" /> (단, u₁u₂u₃ ≠ 0)
  
<br/>

\- 점 A(x₁, y₁, z₁)를 지나고 좌표평면에 평행한 직선의 방정식은 다음과 같다. (단, u₁ ≠ 0 또는 u₂ ≠ 0 또는 u₃ ≠ 0)


|xy평면에 평행(u₁, u₂, 0)|yz평면에 평행(0, u₂, u₃)|zx평면에 평행(u₁, 0, u₃)|
|:----:|:----:|:----:|
|<img src="https://latex.codecogs.com/svg.latex?\frac{x&space;-&space;x_{1}}{u_{1}}&space;=&space;\frac{y&space;-&space;y_{1}}{u_{2}}" title="\frac{x - x_{1}}{u_{1}} = \frac{y - y_{1}}{u_{2}}" />, z = z₁|<img src="https://latex.codecogs.com/svg.latex?\frac{y&space;-&space;y_{1}}{u_{2}}&space;=&space;\frac{z&space;-&space;z_{1}}{u_{3}}" title="\frac{y - y_{1}}{u_{2}} = \frac{z - z_{1}}{u_{3}}" />, x = x₁|<img src="https://latex.codecogs.com/svg.latex?\frac{x&space;-&space;x_{1}}{u_{1}}&space;=&space;\frac{z&space;-&space;z_{1}}{u_{3}}" title="\frac{x - x_{1}}{u_{1}} = \frac{z - z_{1}}{u_{3}}" />, y = y₁|

<br/>

\- 점 A(x₁, y₁, z₁)를 지나고 좌표축에 평행한 직선의 방정식은 다음과 같다. (단, u₁ ≠ 0 또는 u₂ ≠ 0 또는 u₃ ≠ 0)


|x축에 평행(u₁, 0, 0)|y축에 평행(0, u₂, 0)|z축에 평행(0, 0, u₃)|
|:----:|:----:|:----:|
|y = y₁, z = z₁|x = x₁, z = z₁|x = x₁, y = y₁|

<br/>

### 4.평면의 방정식

(1) 법선벡터 : 한 평면과 직각을 이루는 벡터

<br/>

(2) 좌표공간에서 법선벡터가 <img src="https://latex.codecogs.com/svg.latex?\overrightarrow{n}" title="\overrightarrow{n}" /> = (a, b, c)인 x, y, z에 대한 평면의 방정식
  : ax + by + cz + d = 0
  
<br/>

### 5.점과 평면 사이의 거리

: 좌표공간의 한 점에서 해당 점을 지나지 않는 평면에 내린 수선의 발이 있을 때, 점과 수선의 발이 이루는 선분의 길이

<br/>

\- 점 P(<img src="https://latex.codecogs.com/svg.latex?x_{0},&space;y_{0},&space;z_{0}" title="x_{0}, y_{0}, z_{0}" />)과 평면 ax + by + cz + d = 0 사이의 거리


 : <img src="https://latex.codecogs.com/svg.latex?\frac{\left&space;|&space;ax_{0}&space;&plus;&space;by_{0}&space;&plus;&space;cz_{0}&space;&plus;&space;d&space;\right&space;|}{\sqrt{{a^{2}}&space;&plus;&space;{b^{2}}&space;&plus;&space;{c^{2}}}}" title="\frac{\left | ax_{0} + by_{0} + cz_{0} + d \right |}{\sqrt{{a^{2}} + {b^{2}} + {c^{2}}}}" />
 
 <br/>
 
\- 원점과 평면 ax + by + cz + d = 0 사이의 거리
 
 
 : <img src="https://latex.codecogs.com/svg.latex?\frac{\left&space;|&space;d&space;\right&space;|}{\sqrt{{a^{2}}&space;&plus;&space;{b^{2}}&space;&plus;&space;{c^{2}}}}" title="\frac{\left | d \right |}{\sqrt{{a^{2}} + {b^{2}} + {c^{2}}}}" />

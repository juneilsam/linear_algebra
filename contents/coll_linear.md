use_math: true 
comments: true

출처 : 


## 1.벡터

### 1.1.벡터

### 1.2.내적

### 1.3.정사영

<br/>
<br/>

## 2.선형연립방정식

### 2.1.선형연립방정식(Linear System of Equation)

### 2.2.Gauss 소거법과 Gauss-Jordan 소거법

<br/>
<br/>

## 3.행렬과 행렬식

### 3.1.행렬 연산

### 3.2.역행렬

### 3.3.기본행렬

### 3.4.선형연립방정식의 해집합, 특수행렬

### 3.5.행렬식

<br/>
<br/>

## 4.일차독립과 기저(basis) 및 차원(Dimension)

### 4.1.일차독립과 부분공간

### 4.2.기저와 차원

### 4.3.정사영과 최소제곱해(last square soution), QR 분해

<br/>
<br/>

## 5.선형변환(Linear Transformations)

### 5.1.선형변환

### 5.2.핵(kernel)과 치역(range)

<br/>
<br/>

## 6.고윳값, 고유벡터, 대각화(Diagonalization)

### 6.1.고윳값과 고유벡터

### 6.2.닮음 행렬과 행렬의 대각화(Matrix Diagonalization)

### 6.3.직교대각화(Orthogonally diagonalizing)

<br/>
<br/>

## 7.SVD(특이값 분해, 특잇값 분해, singular value decomposition)

### 7.1.특이값 분해

### 7.2.일반화된 역행렬(pseudo-inverse, Moore-Penrose Generalized Inverse)

<br/>
<br/>

## 8.이차형식(quadratic form)

### 8.1.이차형식

<br/>
<br/>

---

## 1.벡터

### 1.1벡터

\- 스칼라(scalar)

    : 크기만 주어지지만 완전히 표시되는 양

    : 길이, 넓이, 질량, 온도


\- 벡터(vector)

    : 크기 뿐만 아니라 방향까지 지정하지 않으면 완전히 표현할 수 없는 양
   
    : 속도, 위치 이동, 힘

    : 벡터는 크기와 방향을 갖는 유향선분(2차원, 3차원 공간의 벡터는 화살표로 표현 가능)

    : 시작점과 끝점이 같아서 크기가 0인 벡터를 영벡터라 한다(영벡터는 크기기 0이므로 방향은 임의의 방향으로 한다)
    
    
 * n차원 벡터(n-dimensional vector)
 
    : n개의 실수의 순서조
    
    : X = (<img src="https://latex.codecogs.com/gif.latex?x_{1}" title="x_{1}" />, <img src="https://latex.codecogs.com/gif.latex?x_{2}" title="x_{2}" />, ..., <img src="https://latex.codecogs.com/gif.latex?x_{n}" title="x_{n}" />), = <img src="https://latex.codecogs.com/gif.latex?\begin{bmatrix}&space;x_{1}\\&space;x_{2}\\&space;\vdots&space;\\&space;x_{n}&space;\end{bmatrix}" title="\begin{bmatrix} x_{1}\\ x_{2}\\ \vdots \\ x_{n} \end{bmatrix}" />
    
    : 이때 실수 <img src="https://latex.codecogs.com/gif.latex?x_{1}" title="x_{1}" />, <img src="https://latex.codecogs.com/gif.latex?x_{2}" title="x_{2}" />, ..., <img src="https://latex.codecogs.com/gif.latex?x_{n}" title="x_{n}" />을 x의 성분이라 한다.


* 벡터의 상등

    : x = <img src="https://latex.codecogs.com/gif.latex?\begin{bmatrix}&space;x_{1}\\&space;x_{2}\\&space;\vdots&space;\\&space;x_{n}&space;\end{bmatrix}" title="\begin{bmatrix} x_{1}\\ x_{2}\\ \vdots \\ x_{n} \end{bmatrix}" />, y = <img src="https://latex.codecogs.com/gif.latex?\begin{bmatrix}&space;y_{1}\\&space;y_{2}\\&space;\vdots&space;\\&space;y_{n}&space;\end{bmatrix}" title="\begin{bmatrix} y_{1}\\ y_{2}\\ \vdots \\ y_{n} \end{bmatrix}" />
    
    : <img src="https://latex.codecogs.com/gif.latex?x_{i}&space;=&space;y_{i}" title="x_{i} = y_{i}" /> (i = 1, 2, ..., n)이면 x = y

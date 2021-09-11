![header](https://capsule-render.vercel.app/api?type=waving&color=auto&height=300&section=header&text=Js%20Study&fontSize=90&animation=fadeIn&fontAlignY=38&desc=%20이성규&descAlignY=65&descAlign=62)

#header
```
![header](https://capsule-render.vercel.app/api?type=waving&color=auto&height=300&section=header&text=Js%20Study&fontSize=90&animation=fadeIn&fontAlignY=38&desc=%20본인의 이름을 넣어주세요&descAlignY=65&descAlign=62)
```
## Navigation
[MadeBy](#MadeBy)
## 대표적인 데이터 구조: 트리

### 1. 트리 (Tree) 구조
- 트리: Node와 Branch를 이용해서, 사이클을 이루지 않도록 구성한 데이터 구조
- 실제로 어디에 많이 사용되나? 
- 트리 중 이진 트리 (Binary Tree) 형태의 구조로, 탐색(검색) 알고리즘 구현을 위해 많이 사용됨

### 2. 알아둘 용어
| 용어 | 의미 | 기타 | 
|---|:---:|---:|
| `Node` | 트리에서 데이터를 저장하는 기본 요소 (데이터와 다른 연결된 노드에 대한 Branch 정보 포함) | | 
| `Root Node` | 트리 맨 위에 있는 노드 |  | 
| `Level` | 최상위 노드를 Level 0으로 하였을 때, 하위 Branch로 연결된 노드의 깊이를 나타냄 | | 
| `Parent Node` | 어떤 노드의 다음 레벨에 연결된 노드 |  |
| `Child Node` | 어떤 노드의 상위 레벨에 연결된 노드 |  |
| `Leaf Node (Terminal Node)` | Child Node가 하나도 없는 노드 |  |
| `Sibling (Brother Node)` | 동일한 Parent Node를 가진 노드 |  |
| `Depth` | 트리에서 Node가 가질 수 있는 최대 Level |  |

<img src="http://www.fun-coding.org/00_Images/tree.png" width="600" />

### 3. 이진 트리와 이진 탐색 트리 (Binary Search Tree)
- 이진 트리: 노드의 최대 Branch가 2인 트리
- 이진 탐색 트리 (Binary Search Tree, BST): 이진 트리에 다음과 같은 추가적인 조건이 있는 트리
  - 왼쪽 노드는 해당 노드보다 작은 값, 오른쪽 노드는 해당 노드보다 큰 값을 가지고 있음!
  
<img src="https://www.mathwarehouse.com/programming/images/binary-search-tree/binary-search-tree-insertion-animation.gif" />

(출처: https://www.mathwarehouse.com/programming/gifs/binary-search-tree.php#binary-search-tree-insertion-node)  

### 4. 자료 구조 이진 탐색 트리의 장점과 주요 용도
- 주요 용도: 데이터 검색(탐색) 
- 장점: 탐색 속도를 개선할 수 있음

> 단점은 이진 탐색 트리 알고리즘 이해 후에 살펴보기로 함

### 이진트리와 정렬된 배열간의 탐색 비교
<img src="https://www.mathwarehouse.com/programming/images/binary-search-tree/binary-search-tree-sorted-array-animation.gif" />

(출처: https://www.mathwarehouse.com/programming/gifs/binary-search-tree.php#binary-search-tree-insertion-node)

### 5. 파이썬 객체지향 프로그래밍으로 링크드 리스트 구현하기
#### 5.1. 노드 클래스 만들기

```python
class Node:
    def __init__(self, value):
        self.value = value
        self.left = None
        self.right = None
```

# MadeBy
* [x] 이성규
* [ ] https://github.com/magmom95
* [ ] https://github.com/magmom7

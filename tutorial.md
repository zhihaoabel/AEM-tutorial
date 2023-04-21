## CRXDE Lite

#### 1.content

- 包含网站结构；
- 指向结构或页面组件的节点（Nodes）；
- cloud版有权限限制；
- ==jcr:content结点的sling:resourceType属性指向源代码的路径；==

#### 2.apps

- 包含开发者写的源代码；
- 包含从JCR获取组件和组装页面的API；
- cloud版需要manager部署到这里，非cloud版不需要；
- 开发者可更改的位置；

#### 3.libs

- AEM自带的源代码；
- 只读，无法写入和更改；

## Touch-optimized UI

N/A
### Tag a page
![[20230420173533.png]]
![[20230420173548.png]]
- 随便选择一个页面，点击properties
![[20230420173739.png]]
![[20230420173809.png]]

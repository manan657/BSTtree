class Node:
    def __init__(self,key):
        self.left = None
        self.right = None
        self.val = key
def insert(root,value):
    if root is None:
        root = Node(value)
    else:
        if(root.val < value):
            if root.right is None:
                root.right = Node(value)
            else:
                insert(root.right,value)
        else:
            if root.left is None:
                root.left = Node(value)
            else:
                insert(root.left,value)
def inOrder(root):
    if root:
        inOrder(root.left)
        print(root.val,end =' ')
        inOrder(root.right)
def preOrder(root):
    if root:
        print(root.val)
        preOrder(root.left)
        preOrder(root.right)
def postOrder(root):
    if root:
        postOrder(root.left)
        postOrder(root.right)
        print(root.val)
r = Node(50)
insert(r,30)
insert(r,20)
insert(r,70)
insert(r,60)
insert(r,80)
preOrder(r)

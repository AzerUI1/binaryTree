# 🌌 Futuristic Binary Tree in C 🌳

Welcome to the **Binary Tree in C Project** – learn, explore, and visualize this powerful data structure!  

---

## 🔹 Features

- 🌟 Insert, Delete, Search Nodes  
- 🌟 Traversals: Inorder, Preorder, Postorder, Level-order  
- 🌟 Advanced Operations: Height, Depth, Leaf Count, Node Count  
- 🌟 Visual Representation of Trees  
- 🌟 Interactive Buttons and Links  

---

## 🚀 Quick Example in C

'''c
#include <stdio.h>
#include <stdlib.h>

struct Node {
    int data;
    struct Node* left;
    struct Node* right;
};

struct Node* createNode(int data){
    struct Node* node = (struct Node*)malloc(sizeof(struct Node));
    node->data = data;
    node->left = node->right = NULL;
    return node;
}

struct Node* insert(struct Node* root, int data){
    if(root == NULL) return createNode(data);
    if(data < root->data) root->left = insert(root->left, data);
    else root->right = insert(root->right, data);
    return root;
}

void inorder(struct Node* root){
    if(root){
        inorder(root->left);
        printf("%d ", root->data);
        inorder(root->right);
    }
}

int main(){
    struct Node* root = NULL;
    root = insert(root, 50);
    insert(root, 30);
    insert(root, 70);
    insert(root, 20);
    insert(root, 40);
    insert(root, 60);
    insert(root, 80);

    printf("Inorder Traversal: ");
    inorder(root);
    return 0;
}

'''
---


🌐 Learn More

http://learn-c.org/
https://www.geeksforgeeks.org/dsa/binary-tree-data-structure/
https://www.youtube.com/results?search_query=binary+tree+c

---



📸 Visual Representation

⚡ Advanced Functions

int height(Node* root); – Compute tree height

int countLeaves(Node* root); – Count leaf nodes

int findMax(Node* root); int findMin(Node* root); – Find max/min value

void levelOrder(Node* root); – BFS Traversal

🔘 Navigation Buttons

<a href="#features"><button style="padding:10px;background-color:#0f0f0f;color:#00ffea;border-radius:5px;">Features</button></a>
<a href="#quick-example-in-c"><button style="padding:10px;background-color:#0f0f0f;color:#ff00ff;border-radius:5px;">Quick Example</button></a>
<a href="#learn-more"><button style="padding:10px;background-color:#0f0f0f;color:#00ff00;border-radius:5px;">Learn More</button></a>

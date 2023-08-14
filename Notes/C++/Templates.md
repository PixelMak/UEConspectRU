Sure! Here are some examples of data structures and algorithms in C++:

### Data Structures

#### Arrays

cCopy code

`#include <iostream>  int main() {     int arr[5] = { 1, 2, 3, 4, 5 };     for (int i = 0; i < 5; i++) {         std::cout << arr[i] << " ";     }     // Output: 1 2 3 4 5     return 0; }`

#### Linked Lists

cCopy code

`#include <iostream>  struct Node {     int data;     Node* next; };  int main() {     Node* head = new Node();     head->data = 1;     head->next = NULL;     Node* second = new Node();     second->data = 2;     second->next = NULL;     head->next = second;     // Traversing the linked list     Node* current = head;     while (current != NULL) {         std::cout << current->data << " ";         current = current->next;     }     // Output: 1 2     return 0; }`

#### Trees

scssCopy code

`#include <iostream>  struct TreeNode {     int val;     TreeNode* left;     TreeNode* right;     TreeNode(int x) : val(x), left(NULL), right(NULL) {} };  int main() {     TreeNode* root = new TreeNode(1);     root->left = new TreeNode(2);     root->right = new TreeNode(3);     root->left->left = new TreeNode(4);     root->left->right = new TreeNode(5);     // Traversing the tree in-order     std::function<void(TreeNode*)> inorder = [&](TreeNode* node) {         if (node == NULL) return;         inorder(node->left);         std::cout << node->val << " ";         inorder(node->right);     };     inorder(root);     // Output: 4 2 5 1 3     return 0; }`

#### Hash Tables

cCopy code

`#include <iostream> #include <unordered_map>  int main() {     std::unordered_map<std::string, int> umap;     umap["apple"] = 3;     umap["banana"] = 5;     umap["orange"] = 2;     std::cout << umap["apple"] << std::endl; // Output: 3     // Iterating over the hash table     for (auto it = umap.begin(); it != umap.end(); it++) {         std::cout << it->first << ": " << it->second << std::endl;     }     // Output: apple: 3, banana: 5, orange: 2     return 0; }`

### Algorithms

#### Sorting

cCopy code

`#include <iostream> #include <algorithm> #include <vector>  int main() {     std::vector<int> v = { 5, 2, 9, 1, 7 };     std::sort(v.begin(), v.end());     for (int i = 0; i < v.size(); i++) {         std::cout << v[i] << " ";     }     // Output: 1 2 5 7 9     return 0; }`

#### Searching

cCopy code

`#include <iostream> #include <algorithm> #include <vector>  int main() {     std::vector<int> v = { 5, 2, 9, 1, 7 };     std::sort(v.begin(), v.end());     if (`
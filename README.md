# Generalized pooling (Mixed, Gated and Tree) by Lee et al.
Experiments on the generalized pooling methodology presented by paper titled "Generalizing Pooling Functions in Convolutional Neural Networks: Mixed, Gated, and Tree"
[https://arxiv.org/abs/1509.08985].
The paper presents the 3 ways of improving the pooling operations in CNN. 
- By using both max and avg pooling since the mix pooling operation outperforms each of these operations. It uses a single variable alpha
for dividing the contribution from the 2 pooling.
- By using gated pooling, which uses a gating function to combine the contributions of the max and avg pooling. The gating is performed by 
using a sigmoid function on top of the mixed pooling 
- Tree pooling which learns the pooling operations in the form of a decision tree.

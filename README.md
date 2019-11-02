# Train CIFAR10 with PyTorch

I'm trying to improve the accuracy and convergence speed of cifar10.

## My optimizer and training model
I use ResNet18 and Ranger(lookahead optimizer+RAdam).
I implemented AMSgrad's method in RAdam.


### attention
If you use this code, you have to add a new file:"cifar10_resnet18.pt" in your folder.



### Reference
Lookahead and ResNet18 reference is (https://github.com/michaelrzhang/lookahead).
RAdam reference is (https://github.com/LiyuanLucasLiu/RAdam).
Thanks.

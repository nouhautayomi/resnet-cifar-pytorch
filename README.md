# Train CIFAR10 with PyTorch

I'm trying to improve the accuracy and convergence speed of cifar10.

# Now accuracy
95.31%

## My optimizer and training model
I use ResNet18 and Ranger(lookahead optimizer+RAdam).
I implemented AMSgrad's method in RAdam.


### attention
If you use this code, you have to add a new file:"cifar10_resnet18.pt" in your folder.



### Reference
[Lookahead](https://github.com/michaelrzhang/lookahead).
[RAdam](https://github.com/LiyuanLucasLiu/RAdam).
[ResNet18/cifar10](https://github.com/uoguelph-mlrg/Cutout)
Thanks all.

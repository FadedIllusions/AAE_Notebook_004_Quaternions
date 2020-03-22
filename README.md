# AAE_Notebook_004_Quaternions
This notebook is a continuation of representing orientation of the vehicle based on its Body Frame.

![quaternions](images/quaternions.png)

As seen in the Euler Angle notebook, a vehicles orientation within the Local Frame can be given by the orientation of the Body Frame. Though, unlike with computationally expensive Rotation Matrices, a single [Quaternion](https://en.wikipedia.org/wiki/Quaternion) accomplishes the same thing, mathematically, as a series of rotation matrix multiplication in a more compact form.

![quaternions](images/quats.png)

Using Quaternions, we can still represent vehicle orientation and changes thereof:

![orientationchange](images/quatinv.png)

Not only can we convert between Quaternions and Rotation Matrices...

![quattorot](images/quattorot.png)

... But, we can also convert Quaternions to Euler Angles

![conversion](images/conversions.png)

And even multiply Quaternions together:

![multiplyingquats](images/multquats.png)

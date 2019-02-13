#### Don't decay the learning rate, increase the batch size

---------------

- While training, decay the learning rate is common practice. This paper suggested that the increase the batch size could have the same effect.

- the randomness of SGD is determined by the fluctuation scale :

$$ g = \epsilon ({N \over B} - 1) $$


- Small batch size well generalize than Large Batch size. (generalization gap) Why?

=> this optimal batch size is arises when the noise scale g ~ e N/B ( when optimal )

$$ {B}_{opt} \propto \epsilon N $$

has linear relationship between ( learning rate and Batch size )


> Ghost batch norm?

: "Ghost Batch Normalization", which creates virtual sub-batches which are each normalized separately.
- This ensures the mean gradient is independent of batch size.

-----------

#### Related Work ( further study )


- Decaying learning rates : [Smith & Le(2017)](https://arxiv.org/pdf/1710.06451.pdf)

- beneficial effect of noise at the start of Training[Keskar et al.(2016)](https://arxiv.org/abs/1609.04836)

-----------

#### Question

- If we increase the batch size - then more sample data added : having the smoothing effect ?

- Between Noise scale and Learning rate relationship

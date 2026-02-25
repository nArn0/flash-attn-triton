flash-attention-triton
======================

Stripped down version of [flash-attention](https://github.com/Dao-AILab/flash-attention) by [Tri Dao](mailto:trid@cs.stanford.edu) to force using the triton implementation even on CUDA devices to bypass the sm_80 minimum architecture.

The `flash_blocksparse_attention` has been removed for now as it depends on the cuda specific parts.
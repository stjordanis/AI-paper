# AI-paper
Paper 1

What’s Hidden in a Randomly Weighted Neural Network?

Reference

[1] https://viblo.asia/p/paper-explain-whats-hidden-in-a-randomly-weighted-neural-network-implement-with-pytorch-Az45bDz6ZxY

Paper 2

Chúng ta thường train models với 32-bit optimization, hay mixed 16-bit với 32-bit optimization, hay còn gọi là Half (mixed) precision (với các GPUs dòng 20XX trở lên). Nếu dùng Pytorch-lightning, mình biết có thể set để train chỉ với 16-bit mà thôi. Gần đây có một số nghiên cứu tập trung vào train models với chỉ 8-bit (quantization) optimization mà không làm giảm prediction performance của các models. Bên cạnh đó, lợi ích của việc train models với giúp tiết kiệm tài nguyên tính toán và có thể triển khai các models trên các thiết bị di động. Đây là bài báo về chủ đề này có tên "8-BIT OPTIMIZERS VIA BLOCK-WISE QUANTIZATION" tại đây https://arxiv.org/pdf/2110.02861.pdf. Họ cũng chia sẽ source code với thư viện có tên bitsandbytes tại đây https://github.com/facebookresearch/bitsandbytes

Reference

[1] https://arxiv.org/pdf/2110.02861.pdf?fbclid=IwAR2Hv4Vb-41eb-Wnf91GeeAAEm4hoGJYGhCOsdLjpFdXc5wJbg5R8pMeJtI

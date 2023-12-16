---
title: "Jumping Shift: A Logarithmic Quantization Method for Low-Power CNN Acceleration"
Date of Conference: 17-19 April 2023
DOI: 10.23919/DATE56975.2023.10137169
venue: '2023 Design, Automation & Test in Europe Conference & Exhibition (DATE)'
paperurl: 'http://avalongxing.github.io/files/Jumping_Shift_A_Logarithmic_Quantization_Method.pdf'
---
Abstract:
Logarithmic quantization for Convolutional Neural Networks (CNN): a) fits well typical weights and activation distributions, and b) allows the replacement of the multiplication operation by a shift operation that can be implemented with fewer hardware resources. We propose a new quantization method named Jumping Log Quantization (JLQ). The key idea of JLQ is to extend the quantization range, by adding a coefficient parameter “s” in the power of two exponents (2sx+i). This quantization strategy skips some values from the standard logarithmic quantization. In addition, we also developed a small hardware-friendly optimization called weight de-zero. Zero-valued weights that cannot be performed by a single shift operation are all replaced with logarithmic weights to reduce hardware resources with almost no accuracy loss. 
To implement the Multiply-And-Accumulate (MAC) operation (needed to compute convolutions) when the weights are JLQ-ed and de-zeroed, a new Processing Element (PE) has been developed. This new PE uses a modified barrel shifter that can efficiently avoid the skipped values. Resource utilization, area, and power consumption of the new PE standing alone are reported. We have found that JLQ performs better than other state-of-the-art logarithmic quantization methods when the bit width of the operands becomes very small.

[Paper can be found here](http://avalongxing.github.io/files/Jumping_Shift_A_Logarithmic_Quantization_Method.pdf)


# Llama-3.2-Medico-BD: Medical Product Assistant for Bangladesh


Fine-tuned version of Llama-3.2-3B for medical product information retrieval in Bangladesh, optimized for brand/generic medicine recommendations and dosage guidance.

## Features
- **QLoRA Fine-Tuning**: 4-bit quantization with `bitsandbytes` for efficient training
- **Medical Dataset**: 1,000+ entries covering Bangladeshi generic/brand names, dosages, manufacturers
- **Streaming Inference**: Real-time text generation with `TextStreamer`
- **PEFT Integration**: Parameter-Efficient Fine-Tuning via `peft`
- **Custom Tokenization**: Optimized for medical terminology in Bangladesh

  
**Key Highlights**  
- Specialized for Bangladeshi pharmaceutical context  
- Memory-efficient training via 4-bit quantization  
- Includes end-to-end workflow from data prep to deployment  
- Optimized for low-resource GPU environments  
- MIT license for commercial/research use

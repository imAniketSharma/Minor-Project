# Curriculum's Minor-Project
## Attention-Based Neural Machine Translation Model

* The Program trains on a Sequence to Sequence model for Spanish to English translation.

* Attention is proposed as a solution to the limitation of the Encoder-Decoder model. 
Encoding the input sequence to one fixed length vector from which to decode each output time step.

* This issue is believed to be more of a problem when decoding long sequences.

* The Input will be a Spanish sentence, such as "¿todavia estan en casa?", and it return Output as the English translation: "are you still at home?"

* Used a language dataset provided by http://www.manythings.org/anki/.

* we propose two simple and effective attentional mechanisms for neural machine translation:-

      1.The global approach which always looks at all source positions and
      
      2.The local one that only attends to a subset of source positions at a time.

* We test the effectiveness of our models in the WMT translation tasks between English and Spanish in both directions.

* Our local attention yields large gains of up to 5.0 BLEU over non-attentional models which already incorporate known techniques such as dropout.

* We have compared various alignment functions and shed light on which functions are best for which attentional models.

* Our analysis shows that attention-based NMT models are superior to non- attentional ones in many cases, for example in translating names and handling long sentences.


# Named entity recognition on a Finnish dataset

For running a BERT based model for a named entity recognition (NER) task. This repository contains the following notebooks:
- data_preprocessing
- named_entity_recognition

To give a better understanding of the form of the data, a reference picture of the data might be released in the future.

Code tested with
- Python 3.7
- Torch 1.7.1
- Transformers 4.16.2

Note that 
- this repository is NOT under active maintenance but merely an archive of the code for related conference paper,
- it should work but has some wonky parts (e.g., naming of valid and test sets should be as described in the conference paper but named the wrong way in the code, unfortunately),
- cleaning up and refactoring the code would be the next logical step if one would like to utilize the code in the notebooks,
- there are python script versions of the code in [this Huggingface tutorial](https://github.com/huggingface/transformers/blob/main/examples/pytorch/token-classification/run_ner_no_trainer.py) where the NER code is also based on.

This code is used in the following conference paper: \
    Toivanen, I., Räsänen, V., Lindroos, J., Oinas, T., & Taipale, S. (2022). Implementing sentiment analysis to an open-ended questionnaire: Case study of digitalization in elderly care during COVID-19. In International Conference of Advanced Research Methods and Analytics. Editorial de la Universitat Politècnica de València. https://ocs.editorial.upv.es/index.php/CARMA/CARMA2022/paper/view/15089

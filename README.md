# NLP-Assignment-6---Student-Layer-Initialization

## Student Info

Ashmita Phuyal(124454)

### Task 1: Student Layer Initialization <br>

We have modified the function distill_bert_weights and added the conditional statements to initialize different layers of the student model based on the specified model_type:<br>
- For model_type == 'top', we initialize the top K layers {1, 2, 3, 4, 5, 6} from the 12-layer teacher model to the 6-layer student model.<br>
- For model_type == 'bottom', we initialize the bottom K layers {7, 8, 9, 10, 11, 12} from the 12-layer teacher model to the 6-layer student model.<br>
- For model_type == 'odd', we initialize the odd layers {1, 3, 5, 7, 8, 9, 11} from the 12-layer teacher model to the 6-layer student model.<br>
Similarly, We have ensured that for each model type, only the specified layers are initialized, leaving the rest of the student model's layers unchanged.

### Task 2: Evaluation and Analysis <br>

| Student Layer |  Training Loss | Validation Loss | Validation Accuracy |
| --- | --- | --- | --- | 
| Top-K Layer | |  | 
| Bottom-K Layer| | ||
| Odd Layer | | |
| Even Layer | | |

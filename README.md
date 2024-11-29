In the domain of inverse problems, traditional sequential pipelines for parameter estimation often introduce approximation errors by treating reconstruction and decision-making as disconnected steps. This project addresses the challenge of integrating task-aware strategies into the reconstruction process by utilizing a bilevel optimization framework that simultaneously optimizes image reconstruction and task performance. While existing approaches like joint learning have attempted to address these limitations, they lack the mathematical flexibility to separate and explicitly optimize reconstruction and task-specific objectives. 

The proposed method employs the Hyperparameter Optimization with Approximate Gradient (HOAG) algorithm, utilizing implicit differentiation to develop a nested optimization structure. The inner level focuses on image reconstruction using smoothed total variation regularization, while the outer level optimizes task-specific metrics. Experimental validation on the Cityscapes and Stanford Dogs datasets demonstrates significant performance improvements in segmentation and classification tasks across varying noise intensities.

This research contributes a flexible, generalizable approach that mitigates traditional pipeline approximation errors and provides a promising framework for future applications in complex inverse problem pipelines.

![image](https://github.com/user-attachments/assets/2028bcbf-b811-4541-9be0-326e88a2bce0)

![image](https://github.com/user-attachments/assets/f06235a7-4a51-4c45-b71e-ff2fd1fd69d4)

![image](https://github.com/user-attachments/assets/18d06d42-20cd-460d-ac30-6eaf6cb22ac3)

![image](https://github.com/user-attachments/assets/8a210f7f-4a3c-4563-a1a5-6b63448a57cc)



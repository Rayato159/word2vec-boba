# Word2Vec Boba

This is to POC in topic of **"Word2Vec"** using N-Gram.

## Word Vector Size:

Word Vector Size: (29, 10)

## Test Sentence:

อย่างสีเหลือง เยลโล่<br>
มะม่วง แมงโก้<br>
เตา อั้งโล่<br>
มีด อีโต้<br>
ไฮลักซ์ รีโว่<br>
เสื้อใน วาโก้<br>
ตกใจ โอ้โห้<br>
นักบอล โรนัลโด้<br>
เยลลี่ ปีโป้<br>
ปั้มน้ำมัน เอสโซ่<br>
แบงก์ กาโม่<br>
ขนม ยูโร่<br>
ของเล่น เลโก้<br>
นายก ฮัลโหลล<br>

## Layers:

Linear(word_to_vec_size, 128, bias=True)<br>
ReLu<br>
Linear(128, 128, bias=True)<br>
ReLu<br>
Linear(128, word_to_vec_size, bias=True)<br>

## Optimizer:
Adam

![alt text](./screenshots/optimizer.png "Adam")

## Accuracy:

Score: 57.14%

![alt text](./screenshots/score.png "Score")
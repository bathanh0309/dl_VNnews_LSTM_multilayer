## Mô hình đa lớp LSTM / Pytorch để phân loại dữ liệu chủ đề tin tức

```bash
Thành viên: Nguyễn Bá Thành
```

Các chủ đề tin tức bao gồm: 
- Thế giới (World)
- Thể thao (Sports)
- Kinh doanh (Business)
- Khoa học & Công nghệ (Science and Technology)
  
```
Train samples: 96,000      Batch size: 128
Val samples: 24,000        Số batch train: 750
Test samples: 7,600        Số batch val: 188
                           Số batch test: 60

Vocab size: 20,000        Num layers: 1
Embedding dim: 100        Dropout rate: 0.3
Hidden dim: 192           Num classes: 4
Max sequence length: 60
```
<img width="1389" height="490" alt="image" src="https://github.com/user-attachments/assets/03f69c7d-ee66-471b-9acd-9cb494be59b4" />

<img width="1489" height="490" alt="image" src="https://github.com/user-attachments/assets/d0e56836-b0bb-4c3a-93d5-4427adc639ea" />

<img width="965" height="789" alt="image" src="https://github.com/user-attachments/assets/c2d976d9-fc17-4427-b107-d273a284c4f8" />

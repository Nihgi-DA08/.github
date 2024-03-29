# TEAM 6 - NIHGI

## MIDTERM PROJECT
Dựa trên dữ liệu của ngân hàng Ấn Độ phân tích rủi ro trong việc cho vay.

## LINK DEMO
<div align='center'>

[Click vào đây để xem chi tiết](https://portugal-hotel-booking.yamiannephilim.com)

</div>

### HÌNH ẢNH DEMO
<p align="center">
<img src='https://raw.githubusercontent.com/Nihgi-DA08/Midterm-Project/main/pic/0.jpg'></img>
</p>

### CODE DEMO
```python
# Try parse to number
def try_prs_int(s):
    return pd.to_numeric(s, errors='coerce').astype('Int64')
```

## CAPSTONE PROJECT
Phân tích về lượng booking khách sạn của Bồ Đào Nha.

### HÌNH ẢNH DEMO
<p align="center">
<img src='https://raw.githubusercontent.com/Nihgi-DA08/Capstone-Project/main/pic/0.png'></img>
</p>

### CODE DEMO
```python
# Create dropdown list
def crt_ddl(col_name, desc, percent='15%', default='All'):
    list = df[col_name].unique().tolist()
    list.append('All')
    return Dropdown(
        options=list,
        value=default,
        description=f'{desc}: ',
        style={'description_width': 'initial'},
        layout={'width': percent, 'margin': '0 auto'})
```

## THÀNH VIÊN
Nhóm NIHGI gồm các thành viên:

<img src='https://raw.githubusercontent.com/Nihgi-DA08/Midterm-Project/main/pic/1.jpg' align='right' width='16%' height='16%'></img>
<div style='display:flex;'>

- Nguyễn Đặng Trường An
- Nguyễn Hồng Phương Nghi
- Trần Văn Ninh (đã rời nhóm)
- Nguyễn Thu Trang
- Lương Thụy Vi (đã rời nhóm)

</div>

## TÍCH HỢP
<img src='https://raw.githubusercontent.com/Nihgi-DA08/Midterm-Project/main/pic/2.png' align='left' width='3%' height='3%'></img>
<div style='display:flex;'>

- Matplotlib » 3.5.2

</div>
<img src='https://raw.githubusercontent.com/Nihgi-DA08/Midterm-Project/main/pic/3.png' align='left' width='3%' height='3%'></img>
<div style='display:flex;'>

- NumPy » 1.21.5

</div>
<img src='https://raw.githubusercontent.com/Nihgi-DA08/Midterm-Project/main/pic/4.png' align='left' width='3%' height='3%'></img>
<div style='display:flex;'>

- Pandas » 1.4.4

</div>
<img src='https://raw.githubusercontent.com/Nihgi-DA08/Capstone-Project/main/pic/5.png' align='left' width='3%' height='3%'></img>
<div style='display:flex;'>

- seaborn » 0.11.2

</div>
<img src='https://raw.githubusercontent.com/Nihgi-DA08/Capstone-Project/main/pic/6.png' align='left' width='3%' height='3%'></img>
<div style='display:flex;'>

- Plotly » 2.9.3

</div>
<img src='https://raw.githubusercontent.com/Nihgi-DA08/Capstone-Project/main/pic/7.png' align='left' width='3%' height='3%'></img>
<div style='display:flex;'>

- scikit-learn » 1.0.2

</div>

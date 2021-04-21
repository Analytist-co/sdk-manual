# New CreativeTalk site journey

ในระบบใหม่อยากให้การ tracking ทำได้ผ่าน query param บน URL bar และ ข้อมูลใน `localStorage`

## Registration
1. ก่อนจะ register user จะเป็น anonymous (ยังไม่ต้องการข้อมูล)

![](images/new_site/1_regis.png)

2. เมื่อทำการกด 3rd registration แล้ว อยากให้มีการบันทึกข้อมูลดังนี้ลง `localStorage`

```sh
# example
ctc_email: xxx@gmail.com
ctc_name: a
ctc_surname: b
ctc_mobile: 0xxxxx
ctc_occupational: engineer
```

![](images/new_site/2_regis_success.png)

3. เมื่อทำการสมัครสำเร็จอยากให้มีการเพิ่ม query param ไปใน url

```sh
# query param
?registraion=success


# example
https://play.creativetalk.rgb72.dev?registraion=success
```

![](images/new_site/3_regis_redirect.png)

## Login

1. ก่อนจะ login user จะเป็น anonymous (ยังไม่ต้องการข้อมูล)

![](images/new_site/1_regis.png)

2. เมื่อทำการกด login แล้ว อยากให้มีการบันทึกข้อมูลดังนี้ลง `localStorage`

```sh
# example
ctc_email: xxx@gmail.com
ctc_name: a
ctc_surname: b
ctc_mobile: 0xxxxx
ctc_occupational: engineer
```

และมีการเพิ่ม query param ไปใน url

```sh
# query param
?login=success

# example
https://play.creativetalk.rgb72.dev?login=success
```

![](images/new_site/3_regis_redirect.png)

## Session visit

```sh
# example
custom_category: video
custom_action: pageview
custom_title: Digital Marketing
```

![](images/new_site/4_content_visit.png)

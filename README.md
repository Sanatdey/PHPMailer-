# PHPMailer-
You can send mail through SMTP(simple mail transfer protocol) server for PHP using this folder.


Procedure:
1. download all the files , and find the "index.php" file in the PHPMailer.
2. You have to edit the "index.php" file and give some data like-
  a)$mail->Host = 'smtp.gmail.com';(for localhost)
  b)$mail->Username = 'yourmailid@gmail.com';(enter you mail id)
  c)$mail->Password = 'yourPassword';(entre your password)
  d)$mail->setFrom('yourmailid@gmail.com', 'Sender');(Mail ID of Sender)
  e)$mail->addAddress('reciverMailid@gmail.com', 'Reciver');(Add a recipient)
  f)$mail->Subject = 'Here is the subject';(the subject of your mail)
  g)$mail->Body    = 'This is the HTML message body <b>in bold!</b>';(boy of your mail)
3. you have to configure you mail settings :
  a)The two step Varification system is must be Disable/off.
  b)Less secure app access features must be Enable/on.
  
  
For any Querys/problem please leave a comment.

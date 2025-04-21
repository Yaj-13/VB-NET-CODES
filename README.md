# VB-NET-CODES

# all the codes for the course

#### variables

```vbnet
' String
Dim name As String = "يزيد"

' antger
Dim age As Integer = 22

' double
Dim GPA As Double = 5.0

' boolean
Dim Adult As Boolean = True

' Date
Dim DOB As Date = #11/15/2002#

' char
Dim First_letter As Char = "ي"c

```

#### messagebox with hello world


```vbnet
MessageBox.Show("Hello World")
```
#### print your name in the messagbox


```vbnet
Dim name As String

name = TextBox1.Text

MessageBox.Show("hello my name is " & name)
```
#### print your name in label


```vbnet
Dim name As String

name = TextBox1.Text

Label1.Text = name
```
#### use the input box


```vbnet
 Dim userName As String
 userName = InputBox("What is your name?", "question")

 MessageBox.Show("it's nuce to meet you " & userName)
```

#### operations


```vbnet
 Dim num1 As Integer
 Dim num2 As Integer
 Dim results As Integer

 num1 = 3
 num2 = 4

 'mathematical
 results = num1 + num2
 MessageBox.Show(results)

 results = num1 - num2
 MessageBox.Show(results)

 results = num1 * num2
 MessageBox.Show(results)

 results = num1 / num2
 MessageBox.Show(results)

 'Assignment Operations (Value Update)
 num1 += 2
 MessageBox.Show(num1)

 num2 -= 3
 MessageBox.Show(num2)
```
#### If statement



#### *note that when you want to use "not equal" you should use (<>)*



##### if else
```vbnet
  Dim age As Integer

 age = InputBox("what is your age", "age checker")

 If age >= 18 Then
     MessageBox.Show("you are an adult")

 Else
     MessageBox.Show("you are a minor")
 End If

```

##### if elseif
```vbnet
 Dim age As Integer

age = InputBox("what is your age", "age checker")

If age <= 13 Then
    MessageBox.Show("you are an minor")

ElseIf 18 > age Then
    MessageBox.Show("you are a teen")

Else
    MessageBox.Show("you are a adult")
End If

```





# Hello-World-(VB)
Code:

Public Class Form1

    Private Sub Button1_Click(sender As Object, e As EventArgs) Handles Button1.Click
        Label2.Visible = False
        DateTimePicker1.Visible = True
        Label3.Visible = True
        Button1.Visible = False
    End Sub

    Private Sub DateTimePicker1_ValueChanged(sender As Object, e As EventArgs) Handles DateTimePicker1.ValueChanged
        Label4.Visible = True
        Label1.Visible = True
        Label3.Visible = False
        DateTimePicker1.Visible = False
    End Sub
End Class

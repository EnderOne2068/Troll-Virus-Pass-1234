Do
    password = InputBox("CRITICAL SYSTEM ERROR!" & vbCrLf & vbCrLf & "Your computer has been seized by the Trollface Syndicate. Enter the decryption key to regain access:", "Troll Virus v1.0")
    
    If password = "1234" Then
        MsgBox "Access Granted. You survived the troll.", 64, "System Restored"
        Exit Do
    Else
        MsgBox "Incorrect Password! The troll is laughing at you.", 16, "Access Denied"
    End If
Loop

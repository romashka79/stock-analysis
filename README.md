# stock-analysis
Sub MacroCheck()
  Dim testMessage As String
  testMessage = "Hello World!"
  MsgBox (testMessage)
  
End Sub

Sub DQAnalysis()

    Worksheets("DQ Analysis").Activate
    
    Range("A1").Value = "DAQ0 (Ticker: DQ)"
    
    'Create a header row
    Cells(3, 1).Value = "Year"
    Cells(3, 2).Value = "Total Daily Volume"
    Cells(3, 3).Value = "Return"
     
End Sub

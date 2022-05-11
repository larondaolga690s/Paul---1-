# Paul---1-
Fill listview For $i = 0 To $iCount_Right - 1     _GUICtrlListView_AddItem($hListView_Right, "Peter " &amp; $i)     _GUICtrlListView_AddSubItem($hListView_Right, $i, "Paul " &amp; $i, 1)     _GUICtrlListView_AddSubItem($hListView_Right, $i, "Mary " &amp; $i, 2)

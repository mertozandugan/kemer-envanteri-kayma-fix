# kemer-envanteri-kayma-fix

>root/uiinventory.py
>Arat:
```
class BeltInventoryWindow(ui.ScriptWindow):
```
>Bul:
```
	def OpenInventory(self):
		self.wndBeltInventoryLayer.Show()
		self.expandBtn.Hide()
```
>Altına Ekle:
```
		self.AdjustPositionAndSize()
```

>Bul:
```
	def CloseInventory(self):
		self.wndBeltInventoryLayer.Hide()
		self.expandBtn.Show()
```
>Altına Ekle:
```
		self.AdjustPositionAndSize()
```

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



https://user-images.githubusercontent.com/64383663/130693047-b223ea9d-9e00-40a5-8c21-ea1e6cf33367.mp4



https://user-images.githubusercontent.com/64383663/130693083-52319fb0-6120-4f1c-b2fa-af25b7cea768.mp4



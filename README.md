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



https://user-images.githubusercontent.com/64383663/130693164-080e850b-cab4-4d1c-b214-64a317dd4faa.mp4



https://user-images.githubusercontent.com/64383663/130693167-69c5f11e-893e-4dfa-8fbc-e207e857b3e0.mp4









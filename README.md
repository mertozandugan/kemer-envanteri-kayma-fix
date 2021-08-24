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

[![Watch the video](https://i.imgur.com/vKb2F1B.png)](https://www.mmotutkunlari.com/data/video/7/7807-2879eddae5696716522c5ed30de13198.mp4)

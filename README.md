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

[![asciicast](https://asciinema.org/a/113463.png)](https://www.mmotutkunlari.com/data/video/7/7806-feaa58ab7687d79d3b58e87cebe6712a.mp4)

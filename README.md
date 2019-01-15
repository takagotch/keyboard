### keyboard
---
https://github.com/boppreh/keyboard

```
pip install keyboard
git clone https://github.com/boppreh/keyboard
```

```py
import keyboard
keyboard.press_and_release('shift+s, space')
keyboard.write('')
keyboard.add_hotkey('ctrl+shift+a', print, args=('', ''))
keyboard.add_hotkey()
keyboard.wait('esc')

add_hotkey(' ', print, args=['space was pressed'])
add_hotkey('space', print, args=['space was pressed'])
add_hotkey('Space', print, args=['space was pressed'])
add_hotkey(57, print, args=['spacing was pressed'])
add_hotkey('ctrl+q', quit)
add_hotkey('ctrl_alt_enter, space', some_callback)

remap('alt+w', 'ctrl_up')

get_hotkey_name(['+', 'left ctrl', 'shift'])

read_hotkey()

get_type_string(record())

add_abbreviation('tm', u'"')
```

```
```



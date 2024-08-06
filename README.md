- 📦 [Components](#components)
  - 📂 [UiButtonComponent](#UiButtonComponent)
  - 📂 [UiIconButtonComponent](#UiIconButtonComponent)
- 📦 [Types](#types)
  - 📂 [UiButtonType](#UiButtonType)
  - 📂 [UiButtonSize](#UiButtonSize)

# Components

## UiButtonComponent

Buttons are native `<button>` or `<a>` elements enhanced with PISA Olympia Design.

**Selector**: `button[ui-button]`

---

@Input()\
type: InputSignal<UiButtonType> = 'primary';
> Button Type

@Input()\
size: InputSignal<UiButtonSize> = 'medium';
> Button Size

@Output()\
click: SignalOutput<MouseEvent>;
> Emits when the user clicks on the button.

## UiIconButtonComponent

Buttons are native `<button>` or `<a>` elements enhanced with PISA Olympia Design.

**Selector**: `button[ui-icon-button]`

---

@Input()\
type: InputSignal<UiButtonType> = 'primary';
> Button Type

@Input()\
size: InputSignal<UiButtonSize> = 'medium';
> Button Size

@Output()\
click: SignalOutput<MouseEvent>;
> Emits when the user clicks on the button.

# Types

## UiButtonType

`'primary' | 'secondary' | 'tertiary'`

## UiButtonSize

`'large' | 'medium' | 'small'`

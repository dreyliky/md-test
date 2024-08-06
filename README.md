- 📦 [Components](#components)
  - 📂 [UiButtonComponent](#UiButtonComponent)
- 📦 [Types](#types)

# Components

## UiButtonComponent

Buttons are native `<button>` or `<a>` elements enhanced with PISA Olympia Design.

**Selector**: `button[ui-button]`

### Inputs

| Name     | Default value | Description |
| -------- | --------      | -------     |
| type: InputSignal<[UiButtonType](#UiButtonType)>     | primary       | Button Type |
| size: InputSignal<[UiButtonType](#UiButtonSize)>     | medium        | Button Size |

### Outputs

| Name     | Data Type     | Description |
| -------- | --------      | -------     |
| click    | MouseEvent    | Emits when user clicks on the button. |

# Types

## UiButtonType

`'primary' | 'secondary' | 'tertiary'`

## UiButtonSize

`'large' | 'medium' | 'small'`

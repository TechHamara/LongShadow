<div align="center">
<h1><kbd>🧩 LongShadow</kbd></h1>
An extension for MIT App Inventor 2.<br>
A component that creates long shadow effects for views with customizable angle, color and gradient.<br><a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://techhamara.blogspot.com/' target='_blank'>Blogger</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Free_Extensions' target='_blank'><small><u>Find More Extension</u></small></a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>
</div>

## 📝 Specifications
* **
📦 **Package:** io.th.longshadow
💾 **Size:** 12.40 KB
⚙️ **Version:** 1.0
📱 **Minimum API Level:** 7
📅 **Updated On:** [date=2025-06-07 timezone="Asia/Calcutta"]
💻 **Built & documented using:** [FAST](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) <small><mark>v2.8.4</mark></small>

![GradientColors_Method](https://github.com/user-attachments/assets/da457634-e9cb-4288-b0f2-3d0df7babc1a)
![ClearGradientColors_Method](https://github.com/user-attachments/assets/d4ca6bda-8359-430d-af5f-07eea47b5646)
![Cleanup_Method](https://github.com/user-attachments/assets/2362539c-a1cb-46a3-b590-f8450f5bb5ea)
![ApplyTextShadow_Method](https://github.com/user-attachments/assets/ae0f8dc7-9e69-4710-b81e-90e7d12a136a)
![TextStyle_Method](https://github.com/user-attachments/assets/d9045213-3150-4e3d-98ca-7015bd47a64b)
![Margins_Method](https://github.com/user-attachments/assets/2fda5fab-3ad5-4df5-81a5-dc4a6d095b4a)
![Initialize_Method](https://github.com/user-attachments/assets/9f97f1df-a2bd-4ce1-aaf0-68154710a41f)
![GradientColors2_Method](https://github.com/user-attachments/assets/e229f87b-2edb-4167-9454-91fb1f1024e8)

-----

![MarginBottom_Set_Property](https://github.com/user-attachments/assets/8f092364-2b5a-4355-86a5-542397b4ff04)
![MarginBottom_Get_Property](https://github.com/user-attachments/assets/b8b403c1-6c91-45cb-91d2-a0906806f152)
![Color_Set_Property](https://github.com/user-attachments/assets/8bf89fb3-7010-4723-8b2b-3128670f07fc)
![Color_Get_Property](https://github.com/user-attachments/assets/196a00b3-401e-41dd-8915-c7e1b10ad831)
![Angle_Set_Property](https://github.com/user-attachments/assets/7c6ecd66-1aee-4d6b-bb70-6fd4a86a3a11)
![Angle_Get_Property](https://github.com/user-attachments/assets/b6d05a42-dfd8-4d69-8957-ba6f31a33dc3)
![TextSize_Set_Property](https://github.com/user-attachments/assets/5b75dc00-44a0-44fa-bcf4-b68a3677f1b6)
![TextColor_Set_Property](https://github.com/user-attachments/assets/80ea3398-d4a4-4d3a-8d9d-0ba4a71b711a)
![Text_Set_Property](https://github.com/user-attachments/assets/90e642aa-12ac-407b-9545-2d98373f38ef)
![Text_Get_Property](https://github.com/user-attachments/assets/4723466d-4db0-4d44-a29a-66e49692151d)
![MarginTop_Set_Property](https://github.com/user-attachments/assets/3fbb73e9-788f-42e2-851a-1d17a025ff99)
![MarginTop_Get_Property](https://github.com/user-attachments/assets/51404881-7aa1-4d81-88f5-9053a6bc0de6)
![MarginRight_Set_Property](https://github.com/user-attachments/assets/4d155e69-c8e1-461f-b41e-220e4a78f189)
![MarginRight_Get_Property](https://github.com/user-attachments/assets/edfe290b-996f-4b81-9526-497aa1570de2)
![MarginLeft_Set_Property](https://github.com/user-attachments/assets/7e752462-734d-4482-8f18-b02545f9d43f)
![MarginLeft_Get_Property](https://github.com/user-attachments/assets/8d9d02fa-aae4-4e67-9db1-543aca353812)



## <kbd>Methods:</kbd>
**LongShadow** has total 8 methods.

### Initialize
Initialize inside an arrangement. This must be called before using other functions.

| Parameter | Type
| - | - |
| arrangement | component

### TextStyle
Sets the text style (0=normal, 1=bold, 2=italic, 3=bold|italic)

| Parameter | Type
| - | - |
| style | number

### GradientColors
Sets gradient colors for the shadow effect. You can provide up to 3 colors.

| Parameter | Type
| - | - |
| color1 | number
| color2 | number
| color3 | number

### GradientColors2
Sets gradient colors for the shadow effect with two colors.

| Parameter | Type
| - | - |
| color1 | number
| color2 | number

### ClearGradientColors
Clears the gradient colors and uses the default shadow color.

### ApplyTextShadow
Applies shadow effect to text

### Cleanup
Cleans up and removes the component from the arrangement

### Margins
Sets all margins at once (left, top, right, bottom) in pixels

| Parameter | Type
| - | - |
| left | number
| top | number
| right | number
| bottom | number

## <kbd>Setters:</kbd>
**LongShadow** has total 9 setter properties.

### Angle
Sets the angle of the shadow effect (0-360 degrees)

* Input type: `number`

### Color
Sets the color of the shadow effect

* Input type: `number`

### Text
Sets the text to display

* Input type: `text`

### TextSize
Sets the text size

* Input type: `number`

### TextColor
Sets the text color

* Input type: `number`

### MarginLeft
Sets the left margin of the text label in pixels

* Input type: `number`

### MarginRight
Sets the right margin of the text label in pixels

* Input type: `number`

### MarginTop
Sets the top margin of the text label in pixels

* Input type: `number`

### MarginBottom
Sets the bottom margin of the text label in pixels

* Input type: `number`

## <kbd>Getters:</kbd>
**LongShadow** has total 7 getter properties.

### Angle
Sets the angle of the shadow effect (0-360 degrees)

* Return type: `number`

### Color
Sets the color of the shadow effect

* Return type: `number`

### Text
Sets the text to display

* Return type: `text`

### MarginLeft
Sets the left margin of the text label in pixels

* Return type: `number`

### MarginRight
Sets the right margin of the text label in pixels

* Return type: `number`

### MarginTop
Sets the top margin of the text label in pixels

* Return type: `number`

### MarginBottom
Sets the bottom margin of the text label in pixels

* Return type: `number`


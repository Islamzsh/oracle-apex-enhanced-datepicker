# oracle-apex-enhanced-datepicker

Enhance your Oracle APEX applications with a feature-rich dual-calendar **item plugin**. Seamlessly toggle between Hijri and Gregorian calendars, delivering a localized, accessible, and user-friendly date selection experience.

### ✅ Key Enhancements

- 🔁 **Dual Calendar Support**  
  Switch between Hijri and Gregorian calendars effortlessly.

- 🌐 **Language Adaptation**  
  The calendar auto-adjusts to Arabic or English based on the APEX session language.

- 🎨 **Modernized UI**  
  Redesigned to match the **Universal Theme** of Oracle APEX for a cohesive look and feel.

---
### ❗ Date Format Rule
- **Do not define a date format** at the item level.  
  The plugin handles formatting internally using APEX's standards.

### 🌍 Language Detection
- Language is determined by the `:FSP_LANGUAGE_PREFERENCE` bind variable.
- You can modify this in the plugin source at **line 53**:
  
  ```plsql
  :FSP_LANGUAGE_PREFERENCE := 'ar-jo';

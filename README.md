# Torque to Weight Calculator

A simple web-based calculator that helps you use a handheld weight scale as a makeshift torque wrench. Perfect for situations where you need to apply a specific torque but don't have a torque wrench handy.

## 🔧 What Does It Do?

This tool calculates the weight you need to apply on a handheld scale at a specific distance from a pivot point to achieve your desired torque.

**Example:** Need to tighten a bolt to 100 Nm? With a 0.5m wrench, you'd need to apply 20.39 kg of force on your scale.

## 📐 How It Works

The calculator uses the fundamental torque equation:

```
Torque (Nm) = Force (N) × Distance (m)
Force (N) = Mass (kg) × 9.81 (gravity)

Therefore:
Weight (kg) = Torque (Nm) ÷ (Distance (m) × 9.81)
```

## 💡 Usage

1. **Measure your arm length** - Distance from the pivot point (bolt center) to where you'll apply force
2. **Enter the required torque** - The torque specification (usually in Newton-meters)
3. **Click Calculate** - The app shows you the weight to apply on your scale
4. **Apply the force** - Push down on your scale at the measured distance until it reads the calculated weight

## ⚠️ Safety Notes

- This method is less precise than a calibrated torque wrench
- Use for non-critical applications only
- Always verify critical torque applications with proper tools
- Ensure your scale is accurate and properly calibrated
- The arm must be perpendicular to the direction of force

---

**Disclaimer:** This tool is provided as-is for informational purposes. Always use proper torque wrenches for critical applications where safety is a concern.
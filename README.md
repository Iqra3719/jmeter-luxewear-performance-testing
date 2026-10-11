# jmeter-luxewear-performance-testing

Performance testing of an E-commerce platform (Luxe Wear inspired) using Apache JMeter - Load, Stress, and CSV-based user testing.

## 📊 Final Result
- **Tool:** Apache JMeter 5.6.3 (Non-GUI)
- **Command:** `jmeter -n -t LuxeWear_LoadTest.jmx -l result.jtl -e -o report`
- **Samples:** 3
- **Error:** 0.00% (100% Pass)
- **Avg Time:** 1008 ms
- **Dashboard:** /report/index.html

## 📸 Dashboard Screenshots
![Dashboard 1](Screenshots/Screenshot%20(343).png)
![Dashboard 2](Screenshots/Screenshot%20(344).png)

## 📁 Project Structure
- `LuxeWear_LoadTest.jmx` - JMeter Test Plan
- `TestData/users.csv` - User data
- `report/` - HTML Dashboard
- `Screenshots/` - Result Screenshots

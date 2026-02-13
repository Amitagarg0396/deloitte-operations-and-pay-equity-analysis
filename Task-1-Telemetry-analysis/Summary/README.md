📊 Task 1: Operational Telemetry Analysis (Tableau)

**1. Business Context**

Daikibo Industrials collected telemetry data from four factories (Tokyo, Osaka, Berlin, Shenzhen) to monitor machine health. Each machine sent a status update every 10 minutes during May 2021.

 -Management wanted to determine:

 -Which factory had the highest downtime?

 -Which machine types were responsible for failures?

**2. Methodology** 

 -Imported unified JSON dataset into Tableau.

 -Created calculated field:

 -Unhealthy = IF [Status] = "Unhealthy" THEN 10 ELSE 0 END

 -Each “Unhealthy” record represents 10 minutes of downtime.

**Built:**

 -Downtime per Factory (Bar Chart)

 -Downtime per Device Type (Bar Chart)

 -Created interactive dashboard using factory-level filter.

**3. Key Findings**

 -Seiko (Osaka) had the highest total downtime.

 -Laser Cutter machines were the primary contributors.

 -Berlin factory showed the lowest operational downtime.

 -Clear variation in reliability across factory locations.

**4. Business Recommendations**

 -Conduct preventive maintenance for Laser Cutter machines.

 -Benchmark Seiko processes against Berlin.

 -Implement predictive maintenance monitoring.

**5. Skills Demonstrated**

 -Tableau Dashboard Design

 -KPI Measurement

 -Root Cause Analysis

 -Business Insight Communication

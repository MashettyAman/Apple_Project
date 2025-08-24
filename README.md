# Apple_Project

# How many units are still under warranty as of today?

SELECT COUNT(*) AS active_warranties
FROM warranty
WHERE warranty_end_date >= CURRENT_DATE;

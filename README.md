# Soil-Testing-Kit
This project is a portable, Raspberry Pi–powered device for real-time soil nutrient analysis using the AS7341 multispectral sensor and colorimetric reagents. Soil health is very important for sustainable agriculture. Traditional soil testing methods are slow, expensive, and unaffordable to many farmers. This project proposes the development of an automated IoT￾based soil testing system, collaborated with multispectral sensors and machine learning (ML) algorithms, to provide real-time nutrient analysis (NPK, pH, organic matter, Micronutrients) and crop-specific fertilizer recommendations.

# Problem Statement
 Conventional or traditional soil testing methods are time-consuming, expensive, and often unable to provide real-time, site-specific data necessary for proper fertilizer management. This leads to inefficient fertilizer use, resulting in economic losses for farmers and environmental degradation due to nutrient runoff and emissions. Existing approaches are labor-intensive and struggle to account for spatial variability across agricultural fields. An AI-integrated system using IoT sensors and spectral analysis can provide immediate, precise soil diagnostics and fertilizer recommendations, enhancing crop yields, promoting 
sustainability, and reducing operational costs. Designed for universal adaptability, the system ensures reliable performance across diverse soils, climates, and cropping systems.

# Objectives
• Rapid testing of soil nutrients N, P, K, pH, organic matter, Fe, Zn, B, S.
• Use AS7341 multispectral sensor (11 band) for colorimetric chemical analysis.
• Integrate a camera-based soil type classifier (texture, color).
• Apply Machine Learning models to recommend fertilizers based on soil results and selected crops.
• Enable IoT-based remote monitoring and cloud data logging.
• Build a touchscreen-based user interface on a Raspberry Pi 4 for easy operation.
• Automate sample shaking, reagent dispensing, and light-isolated sensing.

# Working Principle
1. Soil Sampling: Soil samples are prepared and reagents are automatically added into flask(vials).
2. Spectral Analysis: Color changes are detected by the AS7341 sensor inside a light-proof box.
3. Camera Soil Typing: A camera captures soil texture/color to assist classification.
4. Sensor Data Collection: pH, read real-time N, P, K, pH, organic matter, Ca, Mg, Fe, Zn values.
5. ML Processing: An ML model predicts recommended fertilizer types and quantities based on sensor 
values and crop type.
6. IoT Upload: Results are displayed on-screen and optionally sent to a cloud server.
7. Fertilizer Recommendation: Suggested fertilizers are displayed along with dosage.

# Expected Outcomes
• Reduce soil testing turnaround time from days/weeks to minutes.
• Increase fertilizer efficiency by recommending precise nutrient application.
• Empower farmers with accessible, affordable soil health monitoring.
• scalable platform for micronutrient detection ( Fe, N, P, K, OM).

7. IoT Upload: Results are displayed on-screen and optionally sent to a cloud server.
8. Fertilizer Recommendation: Suggested fertilizers are displayed along with dosage.

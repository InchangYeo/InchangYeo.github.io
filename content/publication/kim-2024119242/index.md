---
title: A hybrid tracking method for maritime obstacles using sensor data
featured: true
authors:
- Ha-Yun Kim
- Myung-Il Roh
- Hye-Won Lee
- admin
- Yeong-Min Jo
- Jisang Ha
- Nam-Sun Son
date: '2024-01-01'
publishDate: '2025-11-06T12:50:15.976891Z'
publication_types:
- article-journal
publication: '*Ocean Engineering*'
doi: https://doi.org/10.1016/j.oceaneng.2024.119242
abstract: Safe navigation of ships depends on the accurate recognition and tracking
  of nearby maritime obstacles as detected by various sensors. Challenges arise in
  tracking maritime obstacles from sensor data because of sensor noise and incomplete
  sensor data. Traditionally, tracking algorithms such as the EKF (Extended Kalman
  Filter) have been applied to track the state of maritime obstacles, including the
  position, COG (Course Over Ground), and SOG (Speed Over Ground). This study implemented
  a combined EKF- and learning-based (hybrid) tracking method. In the EKF-based method,
  the parameters are related to the uncertainty of the system and the sensor data.
  These parameters are generally set manually by analyzing the noise of the sensor
  data and may not be optimal; we optimized the parameters to compensate for this.
  In the learning-based method, we trained a deep learning model using a DNN (Deep
  Neural Network) to predict obstacle states from sensor measurement data. We then
  propose a hybrid tracking method that combines the two tracking methods to compensate
  for the shortcomings of each method. We verified these three tracking methods using
  navigation data obtained through field tests. The verification results showed that
  the learning-based tracking method improved the SOG tracking accuracy by 11.47%
  compared with the traditional EKF-based tracking method. The tracking accuracy of
  the hybrid tracking method was reduced by 22.42% for the COG and 42.05% for the
  SOG. These results indicate that the hybrid tracking method effectively compensates
  for the limitations of the other methods, resulting in an enhanced tracking performance.
tags:
- Maritime obstacle tracking
- Extended kalman filter
- Learning-based tracking
- Ship tracking
- Autonomous ship
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0029801824025800
---

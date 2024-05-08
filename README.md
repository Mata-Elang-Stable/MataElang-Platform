


# MataElang-Platform
# Introduction

Snort is a well-known, signature-based network intrusion detection system (NIDS). The Snort sensor must be placed within the same physical network, and the defense centers in the typical NIDS architecture offer limited network coverage, especially for remote networks with a restricted bandwidth and network policy. Additionally, the growing number of sensor instances, followed by a quick increase in log data volume, has caused the present system to face big data challenges. This research paper proposes a novel design for a cloud-based Snort NIDS using containers and implementing big data in the defense center to overcome these problems. Our design consists of Docker as the sensor’s platform, Apache Kafka as the distributed messaging system, and big data technology orchestrated on lambda architecture. We conducted experiments to measure sensor deployment, optimum message delivery from the sensors to the defense center, aggregation speed, and efficiency in the data-processing performance of the defense center. We successfully developed a cloud-based Snort NIDS and found the optimum method for message delivery from the sensor to the defense center. We also succeeded in developing the dashboard and attack maps to display the attack statistics and visualize the attacks. Our first design is reported to implement the big data architecture, namely, lambda architecture, as the defense center and utilize rapid deployment of Snort NIDS using Docker technology as the network security monitoring platform.


# This project is based on the article: </br>
Saputra, F.A.; Salman, M.; Hasim, J.A.N.; Nadhori, I.U.; Ramli, K. The Next-Generation NIDS Platform: Cloud-Based Snort NIDS Using Containers and Big Data. Big Data Cogn. Comput. 2022, 6, 19. https://doi.org/10.3390/bdcc6010019

# Cite as :

## MDPI and ACS Style

Saputra, F.A.; Salman, M.; Hasim, J.A.N.; Nadhori, I.U.; Ramli, K. The Next-Generation NIDS Platform: Cloud-Based Snort NIDS Using Containers and Big Data. Big Data Cogn. Comput. 2022, 6, 19. https://doi.org/10.3390/bdcc6010019

## AMA Style

Saputra FA, Salman M, Hasim JAN, Nadhori IU, Ramli K. The Next-Generation NIDS Platform: Cloud-Based Snort NIDS Using Containers and Big Data. Big Data and Cognitive Computing. 2022; 6(1):19. https://doi.org/10.3390/bdcc6010019

#Chicago/Turabian Style

Saputra, Ferry A., Muhammad Salman, Jauari A.N. Hasim, Isbat U. Nadhori, and Kalamullah Ramli. 2022. "The Next-Generation NIDS Platform: Cloud-Based Snort NIDS Using Containers and Big Data" Big Data and Cognitive Computing 6, no. 1: 19. https://doi.org/10.3390/bdcc6010019

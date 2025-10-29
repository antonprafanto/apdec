# PROPOSAL SISTEM PENDETEKSI APD (ALAT PELINDUNG DIRI)
## LOKASI TAMBANG DENGAN COMPUTER VISION

---

## 1. EXECUTIVE SUMMARY

### 1.1. Project Overview
Sistem pendeteksi APD berbasis Artificial Intelligence (AI) yang dirancang khusus untuk monitoring kepatuhan penggunaan Alat Pelindung Diri (APD) di area tambang. Sistem ini menggunakan teknologi computer vision dengan single camera placement untuk deteksi real-time secara otomatis dan non-intrusif.

### 1.2. Business Case
- **Problem**: Manual monitoring APD tidak efisien, rentan human error, dan tidak konsisten
- **Solution**: AI-powered automated detection system dengan akurasi >95%
- **ROI**: Penghematan biaya tenaga kerja, pengurangan insiden kerja, compliance reporting otomatis

### 1.3. Key Benefits
-✅ Deteksi real-time 24/7 tanpa henti
-✅ Akurasi deteksi >95% untuk helm, safety vest, dan safety boots
-✅ Data logging otomatis untuk keperluan audit dan reporting
-✅ Alert system yang dapat dikustomisasi
-✅ Integrasi dengan sistem absensi karyawan yang sudah ada
-✅ Scalable untuk multiple camera deployment di masa depan

### 1.4. Service Level Agreement & Guarantees

#### **Performance Guarantees**
- **Detection Accuracy**: Minimum 95% untuk helmet, safety vest, safety boots
- **System Uptime**: 99.5% (excluding planned maintenance)
- **Response Time**: <2 seconds dari detection ke alert
- **False Positive Rate**: <3% dalam normal operating conditions

#### **Support SLA (1-Year Included)**
| Issue Level | Response Time | Resolution Time | Coverage |
|-------------|---------------|-----------------|----------|
| **Critical** | 2 hours | 8 hours | System downtime, detection failure |
| **High** | 4 hours | 24 hours | Performance degradation, accuracy issues |
| **Medium** | 8 hours | 72 hours | Configuration issues, minor bugs |
| **Low** | 24 hours | 5 business days | Documentation, training requests |

#### **Hardware Warranty**
- **Electronic Components**: 3 years on-site replacement
- **Camera System**: 2 years manufacturer warranty + 1 year extended
- **Industrial Equipment**: 2 years parts and labor
- **Power & Network**: 1 year manufacturer warranty

#### **Software Warranty**
- **Bug Fixes**: Lifetime (selama system beroperasi)
- **Model Updates**: Quarterly optimization included
- **Security Patches**: Automatic deployment within 7 days
- **Feature Enhancements**: 2 major releases per year

#### **Client Protections**
- **Performance Penalty**: 1% credit per bulan untuk SLA breach >5%
- **Satisfaction Guarantee**: 30-day performance optimization period
- **Data Protection**: Daily backup dengan 30-day retention
- **Exit Clause**: 6-month notice dengan data export assistance

### 1.5. Implementation Investment & Value Proposition

#### **Turnkey Implementation Package**
**Total Investment: Rp 508.250.000**
- **Project Duration**: 12 weeks dari kick-off hingga go-live
- **Delivery Model**: Complete end-to-end implementation
- **Support**: 1-year comprehensive support included

#### **Investment Breakdown**
| Component | Investment (IDR) | Percentage | Scope |
|-----------|------------------|------------|-------|
| **AI System Development** | Rp 280.000.000 | 55.1% | Custom model training, software development, integration |
| **Hardware Procurement** | Rp 78.250.000 | 15.4% | Enterprise workstation, camera, infrastructure |
| **Implementation Services** | Rp 150.000.000 | 29.5% | Installation, configuration, training, testing |

#### **Expected Business Value**
- **Annual Operational Savings**: Rp 372.000.000
- **5-Year Net Savings**: Rp 1.351.750.000 (setelah deduct investment)
- **ROI Period**: 16.4 months
- **5-Year Return**: 266% pada investasi

#### **Deliverables Included**
- ✅ Custom-trained AI model untuk APD detection (accuracy >95%)
- ✅ Complete hardware system (workstation + camera + infrastructure)
- ✅ Software application dengan real-time dashboard
- ✅ Installation & commissioning di lokasi client
- ✅ Comprehensive training untuk administrators & operators
- ✅ 1-year technical support dengan 4-hour response time
- ✅ System documentation & operating procedures
- ✅ Performance optimization reports (quarterly)
- ✅ Cloud backup integration (500GB, 1 tahun)
- ✅ Future upgrade options untuk multi-camera expansion

---

## 2. TECHNICAL SPECIFICATIONS

### 2.1. Hardware Requirements

#### 2.1.1. Computing Unit (Optimized Enterprise Grade)
**Status**: 🔧 **TO BE DEPLOYED** (Optimized AI Workstation)
- **Chassis**: Industrial-grade 2U rack mount dengan optimal airflow
- **Processor**: Intel Core i7-13700 (16-core, 24-thread) - optimal untuk single camera AI
- **Memory**: 32GB DDR5 5600MHz ECC RAM (sufficient untuk real-time processing)
- **Primary Storage**: 1TB NVMe Gen 4 SSD (OS, applications, database)
- **Data Storage**: 4TB SATA SSD (90-day video retention, ~430GB actual usage)

**Storage Calculation**:
- 4MP @ 30fps = ~2GB/hour
- 24 hours/day = ~48GB/day
- 90 days retention = ~4.3TB required
- **4TB provision provides ~84 days retention at full quality**
- **GPU**: NVIDIA RTX 4070 12GB GDDR6X (optimal untuk 4MP @ 30fps YOLOv8 real-time)
- **OS**: Windows 11 Pro OEM / Ubuntu 22.04 LTS
- **Cooling System**: Industrial-grade air cooling (low maintenance, 24/7 reliable)
- **Power Supply**: 850W 80+ Gold dengan redundant protection
- **Network**: Dual 1GbE Ethernet dengan automatic failover
- **Remote Management**: Intel vPro platform (built-in remote management)
- **Backup System**: Automatic cloud backup integration (500GB included)
- **Warranty**: 3-year on-site business support dengan 24/7 hardware replacement
- **Power Consumption**: ~250W under load (energy efficient untuk 24/7 operation)
- **Noise Level**: <35dB (suitable untuk office/indoor environment)

#### 2.1.2. Camera System
**Type**: IP Camera Industrial Grade
- **Model**: Hikvision DS-2CD2043G2-I (4MP, IP67, IK10)
- **Resolution**: 4MP (2688×1520) @ 30fps
- **Lens**: 2.8mm wide angle (diagonal view: 103°)
- **Night Vision**: Up to 30m with EXIR technology
- **Weather Proof**: IP67 rating untuk outdoor installation
- **Connectivity**: PoE (Power over Ethernet)
- **Smart Features**: Built-in motion detection, tampering detection

#### 2.1.3. Lighting System
**Type**: LED Floodlight Industrial
- **Brand**: Philips Master LED
- **Power**: 50W (5000-7000 lumens)
- **Color Temperature**: 5000K (daylight)
- **Beam Angle**: 120°
- **IP Rating**: IP65
- **Voltage**: 220V AC dengan UPS backup

#### 2.1.4. Network Infrastructure
- **Switch**: D-Link DGS-108 (8-Port Gigabit Switch)
- **Cabling**: Cat6 Ethernet cable (30 meters)
- **PoE Injector**: TP-Link TL-PoE150S (jika switch tidak support PoE)
- **UPS**: APC Back-UPS 600VA untuk backup power

### 2.2. Software Architecture

#### 2.2.1. Core System Components
```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Camera Input  │───▶│  Frame Processor │───▶│   AI Inference  │
└─────────────────┘    └──────────────────┘    └─────────────────┘
                                                        │
                                                        ▼
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│  Alert System   │◀───│ Compliance Engine │◀───│  Data Logger    │
└─────────────────┘    └──────────────────┘    └─────────────────┘
```

#### 2.2.2. Technology Stack
- **Programming Language**: Python 3.9+
- **Computer Vision**: OpenCV 4.8+, YOLOv8
- **Deep Learning**: PyTorch 2.0+, CUDA 12.1
- **Database**: PostgreSQL 15 untuk production, SQLite untuk development
- **Web Framework**: Streamlit untuk dashboard
- **API**: FastAPI untuk integration dengan external systems
- **Message Queue**: Redis untuk real-time alert processing

#### 2.2.3. AI Model Specifications
**Primary Detection Model**: YOLOv8n (Nano) - Optimized for real-time
- **Inference Time**: <50ms per frame
- **Accuracy**: 95.2% mAP (mean Average Precision)
- **Classes**:
  - Helmet (Safety Helmet)
  - Safety Vest (High-visibility vest)
  - Safety Boots
  - Person (Body detection)
- **Training Dataset**: COCO + Custom dataset (min. 2000 images per class)

**Secondary Model**: MediaPipe Pose untuk pose estimation
- **Purpose**: Detect improper wearing of equipment
- **Features**: 33 body landmarks tracking
- **Performance**: Real-time 30fps

### 2.3. System Features

#### 2.3.1. Detection Capabilities
1. **Helmet Detection**
   - Safety helmet compliance
   - Proper helmet wearing verification
   - Color classification (mandatory yellow/orange)

2. **Safety Vest Detection**
   - High-visibility vest detection
   - Reflective strip verification
   - Zipper/closure status check

3. **Safety Boots Detection**
   - Steel-toe boots identification
   - Footwear coverage verification

4. **Person Detection & Tracking**
   - Multiple person tracking simultaneously
   - Face blurring for privacy compliance
   - Employee ID integration with badge system

#### 2.3.2. Alert System
1. **Real-time Alerts**
   - Visual alert di dashboard
   - Audio alarm dengan custom voice message
   - SMS/WhatsApp notification untuk supervisor

2. **Escalation Protocol**
   - Level 1: Gentle reminder (30 seconds)
   - Level 2: Warning alert (1 minute)
   - Level 3: Critical alert (5 minutes - supervisor notification)

3. **Compliance Reporting**
   - Daily/weekly/monthly compliance reports
   - Individual employee compliance tracking
   - Trend analysis and predictive compliance metrics

---

## 3. IMPLEMENTATION PLAN

### 3.1. Project Timeline (12 Weeks)

#### Phase 1: Setup & Infrastructure (Week 1-3)
- [ ] Hardware procurement and delivery (2 weeks)
- [ ] Site preparation and installation (1 week)
- [ ] Network setup and configuration
- [ ] Development environment setup
- [ ] Camera positioning and calibration

#### Phase 2: AI Model Development (Week 4-7)
- [ ] Dataset collection and preparation (2 weeks)
- [ ] Model training and validation (2 weeks)
- [ ] Integration testing with camera feed (1 week)
- [ ] Performance optimization and tuning (1 week)

#### Phase 3: Software Development (Week 8-10)
- [ ] Core detection engine development (2 weeks)
- [ ] Alert system implementation (1 week)
- [ ] Dashboard and reporting interface (1 week)
- [ ] Database design and implementation (1 week)

#### Phase 4: Testing & Deployment (Week 11-12)
- [ ] Comprehensive system testing (1 week)
- [ ] User acceptance testing (UAT) (3 days)
- [ ] Production deployment and go-live (2 days)
- [ ] Staff training and documentation handover

### 3.2. Success Metrics
- **Detection Accuracy**: >95% for all APD categories
- **False Positive Rate**: <3%
- **System Uptime**: >99.5%
- **Response Time**: <2 seconds from detection to alert
- **User Adoption**: >90% compliance within first month

---

## 4. OPERATIONAL PROCEDURES

### 4.1. Daily Operations
1. **System Health Check** (Automated)
   - Camera connection status
   - GPU performance monitoring
   - Storage capacity check
   - Network connectivity verification

2. **Shift Procedures**
   - Pre-shift system validation
   - Backup creation before shift change
   - Alert configuration updates
   - Daily compliance report generation

### 4.2. Maintenance Schedule
- **Daily**: Automated system health check
- **Weekly**: Camera lens cleaning, log review
- **Monthly**: Software updates, performance tuning
- **Quarterly**: Hardware inspection, system calibration
- **Annually**: Full system audit and upgrade assessment

### 4.3. Data Management & Privacy
- **Data Retention**: 90 days for video footage, 5 years for compliance logs
- **Privacy Compliance**: Face blurring, GDPR-like data protection
- **Security**: AES-256 encryption, role-based access control
- **Backup Strategy**: Daily incremental backup, weekly full backup

---

## 5. RISK ASSESSMENT & MITIGATION

### 5.1. Technical Risks
| Risk | Probability | Impact | Mitigation Strategy |
|------|-------------|--------|---------------------|
| Camera failure | Medium | High | Redundant camera, preventive maintenance |
| GPU malfunction | Low | Critical | Backup cloud processing, warranty coverage |
| Software bugs | Medium | Medium | Rigorous testing, rollback procedures |
| Network downtime | Medium | High | Offline mode capability, cellular backup |

### 5.2. Operational Risks
| Risk | Probability | Impact | Mitigation Strategy |
|------|-------------|--------|---------------------|
| Employee resistance | High | Medium | Training, incentive programs |
| False detections | Medium | Medium | Model retraining, threshold tuning |
| Environmental factors | Low | Medium | Weatherproof housing, regular cleaning |
| Power outages | Medium | High | UPS backup, generator connectivity |

---

## 6. TRAINING & DOCUMENTATION

### 6.1. Training Programs
1. **Administrator Training** (2 days)
   - System configuration and maintenance
   - Troubleshooting common issues
   - Report generation and analysis
   - Backup and recovery procedures

2. **Operator Training** (1 day)
   - Daily system operation
   - Alert response procedures
   - Basic troubleshooting
   - Safety protocols

3. **Employee Awareness** (30 minutes)
   - System purpose and benefits
   - Proper APD wearing guidelines
   - Alert system understanding

### 6.2. Documentation Package
- **User Manual**: Comprehensive operation guide
- **Technical Manual**: System architecture and maintenance
- **SOP Documentation**: Standard operating procedures
- **Emergency Procedures**: Critical incident response
- **API Documentation**: Integration guide for developers

---

## 7. FUTURE SCALABILITY

### 7.1. Expansion Opportunities
- **Multi-camera Deployment**: Expand to multiple locations
- **Mobile Integration**: Smartphone app for supervisors
- **Advanced Analytics**: Predictive compliance modeling
- **IoT Integration**: Smart sensors integration
- **Cloud Migration**: Hybrid cloud architecture

### 7.2. Technology Roadmap
- **Year 1**: Single camera deployment optimization
- **Year 2**: Multi-camera integration
- **Year 3**: AI model upgrades and additional APD detection
- **Year 4**: Advanced analytics and reporting
- **Year 5**: Full IoT ecosystem integration

---

## 8. PROJECT TEAM & RESPONSIBILITIES

### 8.1. Project Team Structure
- **Project Manager**: Overall project coordination
- **AI/ML Engineer**: Model development and optimization
- **Software Developer**: Application development
- **Network Engineer**: Infrastructure setup and maintenance
- **Safety Officer**: Requirements validation and compliance
- **Database Administrator**: Data management and security

### 8.2. Stakeholder Management
- **Mine Management**: Regular progress updates and ROI reporting
- **Safety Department**: Compliance requirements and validation
- **IT Department**: Technical support and infrastructure
- **HR Department**: Training coordination and policy implementation
- **Employee Representatives**: User feedback and adoption support

---

*Prepared by: Anton Prafanto, M.T., Senior AI/ML Solutions Architect*
*Date: October 29, 2025*
*Project Code: APD-DETECTOR-2025-01*

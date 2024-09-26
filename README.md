# 呼吸机数据集

## 项目描述
本项目包含为医学呼吸机数据集用于医疗研究和分析，这些数据集为AI驱动的呼吸机临床决策支持研究而设计，旨在提升医疗决策的准确性和效率。

## 文件结构
├─  README.md         # 项目说明文件
---
├─ Patient_Info.csv   #包含患者的基本信息和一些基本的医疗数据。
---
├─ Discrete_Data.csv#包含详细的呼吸机离散数据（如呼吸模式），间断数据（如分钟通气量、呼吸频率等）及对应参数设置
---
└──Continuous_Data.csv #连续数据（如气道压力、流速、潮气量波形数据）（未上传）
---

## 数据关联
这数据集通过以下字段关联：
- **VisitNumber**: 访问编号
- **StartTime**: 开始时间
- **EndTime**: 结束时间

## 申请方式
1. **授权**: 只有获得相应权限的人员才能访问这些数据。
2. **申请流程**:
   - **发送申请**: 需要发送访问申请至[管理员邮箱](mailto:zhaoweiyi2577@outlook.com)，包括申请人的详细信息、申请目的、预期使用数据的时间段等。
   - **审核**: 申请将由数据管理小组进行审核，确保申请符合隐私保护和数据使用政策。
   - **签署协议**: 审核通过后，申请人将获得数据的访问权限。
   - 
## 加密解密说明
为了保护数据隐私和安全，我们使用  [git-crypt](https://github.com/AGWA/git-crypt) 来加密敏感数据文件。
在提交申请通过后才能访问这些数据，我们会将密钥放在附件，具体解锁流程参考 [git-crypt文档](https://github.com/AGWA/git-crypt)

## 安全警告
1. **数据隐私**: 这些文件包含敏感的个人健康信息。未经授权的访问或泄露这些信息可能导致严重的隐私侵犯。
2. **使用限制**: 这些数据仅供授权的人员使用，用于医疗研究和分析。

## 使用说明
- 在使用这些数据之前，请确保你已经获得了必要的授权。
- 请在安全的环境下处理这些数据，避免未经授权的访问。
- 请定期备份数据，并在不再需要时安全地销毁数据。

## 技术支持
- 如果在使用数据过程中遇到任何技术问题，请联系技术支持团队。

## 贡献指南
- 如果您希望为该项目做出贡献，请提交Pull Request或创建Issue。
  
## 联系方式
- **技术支持邮箱**: [管理员邮箱](mailto:zhaoweiyi2577@outlook.com)

## 依赖
- 该项目可能需要以下依赖，请确保您的系统已安装：
  - Excel或兼容软件来查看csv文件

## 安装指南
1. 克隆或下载项目到本地。
2. 使用适当的软件打开数据文件。

# Ventilator Dataset

## Project Description
This project encompasses a medical ventilator dataset for healthcare research and analysis. These datasets are specifically tailored for AI-driven research in clinical decision support for ventilators, with the goal of improving the precision and efficiency of medical decision-making.

## File Structure
├── README.md         # Project documentation file
---
├── Patient_Info.csv   # Contains basic patient information and some basic medical data.
---
├── Discrete_Data.csv # Contains detailed ventilator discrete data (such as breathing patterns), intermittent data (such as minute ventilation, respiratory rate, etc.) and corresponding parameter settings
---
└── Continuous_Data.csv # Continuous data (such as airway pressure, flow rate, tidal volume waveform data) (coming soon)
---

## Data Association
These datasets are associated through the following fields:
- **VisitNumber**: Visit identification number
- **StartTime**: Start time
- **EndTime**: End time

## Application Method
1. **Authorization**: Only authorized personnel can access these data.
2. **Application Process**:
   - **Submit Application**: An access request must be sent to the [administrator's email](mailto:zhaoweiyi2577@outlook.com), including the applicant's detailed information, purpose of application, and the expected period of data usage.
   - **Review**: The application will be reviewed by the data management team to ensure compliance with privacy protection and data usage policies.
   - **Sign Agreement**: After the review is passed, the applicant will be granted access to the data.

## Encryption and Decryption Instructions
To protect data privacy and security, we use [git-crypt](https://github.com/AGWA/git-crypt) to encrypt sensitive data files.
Access to these data is granted after the application is approved, and we will send the key in the attachment. For the specific unlocking process, please refer to the [git-crypt documentation](https://github.com/AGWA/git-crypt).

## Security Warnings
1. **Data Privacy**: These files contain sensitive personal health information. Unauthorized access or disclosure of this information could lead to serious privacy violations.
2. **Usage Restrictions**: These data are for authorized personnel only and are intended for medical research and analysis.

## Usage Instructions
- Ensure you have the necessary authorization before using this data.
- Handle this data in a secure environment to prevent unauthorized access.
- Regularly back up data and securely destroy it when no longer needed.

## Technical Support
- If you encounter any technical issues while using the data, please contact the technical support team.

## Contribution Guidelines
- If you wish to contribute to this project, please submit a Pull Request or create an Issue.

## Contact Information
- **Technical Support Email**: [Administrator's Email](mailto:zhaoweiyi2577@outlook.com)

## Dependencies
- This project may require the following dependencies, please ensure your system has them installed:
  - Excel or compatible software to view csv files

## Installation Guide
1. Clone or download the project to your local machine.
2. Use appropriate software to open the data files.

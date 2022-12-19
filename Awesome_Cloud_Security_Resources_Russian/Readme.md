<br/>
<div align="center">

Кураторский список потрясающих ресурсов, связанных с облачной безопасностью.
</div>
<br/>

# 🛡️ Ресурсы по облачной безопасности ⚔️

# Указатель
- [Стандарты](#Стандарты)
- [Инструменты](#Инструменты)
- [Материалы для чтения](#Материалы-для-чтения)
- [Ресурс](#Ресурс)

# Стандарты

* [CSA STAR](https://cloudsecurityalliance.org/star/)
* [ISO/IEC 27017:2015](https://www.iso.org/standard/43757.html)
* [ISO/IEC 27018:2019](https://www.iso.org/standard/76559.html)
* [MTCS SS 584](https://www.imda.gov.sg/regulations-and-licensing-listing/ict-standards-and-quality-of-service/IT-Standards-and-Frameworks/ComplianceAndCertification)
* [CIS Benchmark](https://www.cisecurity.org/cis-benchmarks/)

# Инструменты
- [Инфраструктура](#Инфраструктура)
- [Контейнер](#Контейнер)
- [SaaS](#saas)
- [Xакинг/обучение](#Xакинг/обучение)
- [Oблачных](#Oблачных)

## Инфраструктура
* [aws_pwn](https://github.com/dagrz/aws_pwn): Инструменты и методы тестирования безопасности AWS.
* [aws_ir](https://github.com/ThreatResponse/aws_ir): Устанавливаемая на Python утилита командной строки для предотвращения компрометации экземпляров.
* [aws-firewall-factory](https://github.com/globaldatanet/aws-firewall-factory): Развертывайте, обновляйте и размещайте свои WAF, управляя ими централизованно через FMS.
* [aws-vault](https://github.com/99designs/aws-vault): Хранилище для безопасного хранения учетных данных AWS и доступа к ним в средах разработки.
* [awspx](https://github.com/FSecureLABS/awspx): Графический инструмент для визуализации эффективных отношений доступа и ресурсов в AWS.
* [azucar](https://github.com/nccgroup/azucar): Инструмент аудита безопасности для Azure.
* [checkov](https://github.com/bridgecrewio/checkov): Инструмент статического анализа кода для инфраструктуры как кода.
* [cloud-forensics-utils](https://github.com/google/cloud-forensics-utils): Библиотека Python для DF и IR в облаке.
* [Cloud-Katana](https://github.com/Azure/Cloud-Katana): Автоматизируйте выполнение шагов моделирования в гибридных облачных средах.
* [cloudlist](https://github.com/projectdiscovery/cloudlist): Список активов от нескольких облачных провайдеров.
* [Cloud Sniper](https://github.com/cloud-sniper/cloud-sniper): Платформа, предназначенная для управления облачными операциями безопасности.
* [Cloudmapper](https://github.com/duo-labs/cloudmapper): Проанализируйте свои среды AWS.
* [Cloudmarker](https://github.com/cloudmarker/cloudmarker): Инструмент и инфраструктура облачного мониторинга.
* [Cloudsploit](https://github.com/aquasecurity/cloudsploit): Проверки конфигурации облачной безопасности.
* [CloudQuery](https://github.com/cloudquery/cloudquery): Инвентаризация облачных ресурсов с открытым исходным кодом с набором готовых политик SQL для обеспечения безопасности и соответствия требованиям.
* [Cloud-custodian](https://github.com/cloud-custodian/cloud-custodian): Механизм правил для облачной безопасности, оптимизации затрат и управления.
* [consoleme](https://github.com/Netflix/consoleme): Плоскость центрального управления для разрешений и доступа AWS.
* [cs suite](https://github.com/SecurityFTW/cs-suite): Инструмент для аудита состояния безопасности AWS/GCP/Azure.
* [Deepfence ThreatMapper](https://github.com/deepfence/ThreatMapper): Apache v2, мощный сканер уязвимостей во время выполнения для Kubernetes, виртуальных машин и бессерверных приложений.
* [dftimewolf](https://github.com/log2timeline/dftimewolf): Мультиоблачная среда для организации криминалистического сбора, обработки и экспорта данных.
* [diffy](https://github.com/Netflix-Skunkworks/diffy): Diffy — это инструмент цифровой криминалистики и реагирования на инциденты (DFIR), разработанный Netflix.
* [ElectricEye](https://github.com/jonrau1/ElectricEye): Постоянно отслеживайте конфигурации сервисов AWS.
* [Forseti security](https://github.com/forseti-security/forseti-security): Инструмент мониторинга ресурсов GCP и обеспечения соблюдения правил.
* [Hammer](https://github.com/dowjones/hammer): Инструмент облачной безопасности с несколькими учетными записями для AWS. Он выявляет неправильные конфигурации и незащищенные данные в самых популярных ресурсах AWS.
* [kics](https://github.com/Checkmarx/kics): Выявляйте уязвимости в системе безопасности, проблемы с соблюдением нормативных требований и неправильные конфигурации инфраструктуры на ранних этапах цикла разработки вашей инфраструктуры как кода.
* [Matano](https://github.com/matanolabs/matano): Бессерверная платформа озера безопасности с открытым исходным кодом на AWS, которая позволяет принимать, хранить и анализировать данные в озере данных Apache Iceberg, а также выполнять обнаружение Python в реальном времени в виде кода.
* [Metabadger](https://github.com/salesforce/metabadger): Предотвращайте атаки SSRF на AWS EC2 с помощью автоматического обновления до более безопасной службы метаданных экземпляров версии 2 (IMDSv2).
* [Open policy agent](https://www.openpolicyagent.org/): Инструмент управления на основе политик.
* [pacbot](https://github.com/tmobile/pacbot): Политика как Code Bot.
* [pacu](https://github.com/RhinoSecurityLabs/pacu): Платформа эксплуатации AWS.
* [Prowler](https://github.com/toniblyx/prowler): Инструмент командной строки для AWS Security Best Practices Assessment, Auditing, Hardening and Forensic Readiness Tool.
* [ScoutSuite](https://github.com/nccgroup/ScoutSuite): Мультиоблачный инструмент аудита безопасности.
* [Security Monkey](https://github.com/Netflix/security_monkey): Отслеживает организации AWS, GCP, OpenStack и GitHub на наличие активов и их изменений с течением времени.
* [SkyWrapper](https://github.com/cyberark/SkyWrapper): Инструмент помогает обнаруживать подозрительные формы создания и использования временных токенов в AWS.
* [Smogcloud](https://github.com/BishopFox/smogcloud): Найдите облачные ресурсы, которые никому не нужны.
* [Steampipe](https://github.com/turbot/steampipe): Postgres FDW, который сопоставляет API с SQL, а также наборы plugin API и моды соответствия для AWS/Azure/GCP и многих других.
* [Terrascan](https://github.com/accurics/terrascan): Выявляйте нарушения нормативных требований и безопасности в рамках инфраструктуры как кода, чтобы снизить риски, прежде чем создавать собственную облачную инфраструктуру.
* [tfsec](https://github.com/liamg/tfsec): Сканер безопасности на базе статического анализа для кода Terraform.
* [Zeus](https://github.com/DenizParlak/Zeus): Инструмент аудита и усиления безопасности AWS.

## Контейнер
* [auditkube](https://github.com/opszero/auditkube): Аудит для EKS, AKS и GKE на соответствие HIPAA/PCI/SOC2 и облачную безопасность.
* [Falco](https://github.com/falcosecurity/falco): Безопасность во время выполнения контейнера.
* [mkit](https://github.com/darkbitio/mkit): Управляемый инструмент проверки kubernetes.
* [Open policy agent](https://www.openpolicyagent.org/): Инструмент управления на основе политик.

## SaaS
* [aws-allowlister](https://github.com/salesforce/aws-allowlister): Автоматически компилируйте политику управления сервисами AWS с предпочитаемыми вами платформами соответствия.
* [binaryalert](https://github.com/airbnb/binaryalert): Бессерверный сканер Yara S3.
* [cloudsplaining](https://github.com/salesforce/cloudsplaining): Инструмент оценки безопасности AWS IAM, который выявляет нарушения минимальных привилегий и создает отчет с приоритетом риска.
* [Cloud Guardrails](https://github.com/salesforce/cloud-guardrails): Быстро отбирайте средства безопасности в облаке, создавая файлы Terraform, которые создают Инициативы политик Azure.
* [Function Shield](https://github.com/puresec/FunctionShield): Библиотека защиты/обнаружения функции aws lambda и gcp.
* [FestIN](https://github.com/cr0hn/festin): Поиск ведра S3 и обнаружение контента.
* [GCPBucketBrute](https://github.com/RhinoSecurityLabs/GCPBucketBrute): Скрипт для перечисления сегментов Google Storage.
* [IAM Zero](https://github.com/common-fate/iamzero): Обнаруживает проблемы с идентификацией и управлением доступом и автоматически предлагает политики наименьших привилегий.
* [Lambda Guard](https://github.com/Skyscanner/LambdaGuard): Инструмент аудита AWS Lambda.
* [Policy Sentry](https://github.com/salesforce/policy_sentry): Генератор политик наименьших привилегий IAM.
* [S3 Inspector](https://github.com/kromtech/s3-inspector): Инструмент для проверки разрешений корзины AWS S3.
* [Serverless Goat](https://github.com/OWASP/Serverless-Goat): Бессерверное приложение, демонстрирующее распространенные недостатки безопасности без сервера.
* [SkyArk](https://github.com/cyberark/SkyArk): Инструмент, помогающий обнаруживать, оценивать и защищать наиболее привилегированные объекты в Azure и AWS.

## Xакинг/обучение
* [ccat](https://github.com/RhinoSecurityLabs/ccat): Инструмент атаки на облачный контейнер.
* [CloudBrute](https://github.com/0xsha/CloudBrute): Перечислитель нескольких облаков.
* [cloudgoat](https://github.com/RhinoSecurityLabs/cloudgoat): «Уязвимый по дизайну» инструмент развертывания AWS.
* [Leonidas](https://github.com/FSecureLABS/leonidas): Фреймворк для выполнения действий злоумышленника в облаке.
* [Sadcloud](https://github.com/nccgroup/sadcloud): Инструмент для развертывания небезопасной инфраструктуры AWS с помощью Terraform.
* [TerraGoat](https://github.com/bridgecrewio/terragoat): Репозиторий Terraform «Уязвимый по замыслу» компании Bridgecrew.
* [WrongSecrets](https://github.com/commjoen/wrongsecrets): Уязвимое приложение, демонстрирующее, как не использовать секреты. С поддержкой AWS/Azure/GCP.

## Oблачных
* AWS
  * [Artifact](https://aws.amazon.com/artifact/): Самообслуживание отчета о соответствии.
  * [Audit manager](https://aws.amazon.com/audit-manager/): Постоянно проверяйте использование AWS.
  * [Certificate Manager](https://aws.amazon.com/certificate-manager/): Частный ЦС и служба управления сертификатами.
  * [CloudTrail](https://aws.amazon.com/cloudtrail/): Записывайте и регистрируйте вызовы API на AWS.
  * [Config](https://aws.amazon.com/config/): Мониторинг взаимосвязи конфигурации и ресурсов.
  * [Elastic Disaster Recovery](https://aws.amazon.com/disaster-recovery/): Сервис восстановления приложений.
  * [Detective](https://aws.amazon.com/detective/): Анализируйте и визуализируйте данные безопасности и помогайте расследованиям безопасности.
  * [Firewall Manager](https://aws.amazon.com/firewall-manager/): Служба управления брандмауэром.
  * [GuardDuty](https://aws.amazon.com/guardduty/): Cервис ИДС.
  * [CloudHSM](https://aws.amazon.com/cloudhsm/): Cервис ХСМ.
  * [Inspector](https://aws.amazon.com/inspector/): Служба обнаружения и оценки уязвимостей.
  * [KMS](https://aws.amazon.com/kms/): Cервис KMS.
  * [Macie](https://aws.amazon.com/macie/): Полностью управляемая служба безопасности и конфиденциальности данных для S3.
  * [Network Firewall](https://aws.amazon.com/network-firewall/): Служба сетевого брандмауэра.
  * [Secret Manager](https://aws.amazon.com/secrets-manager/): Служба управления учетными данными.
  * [Security Hub](https://aws.amazon.com/security-hub/): Служба интеграции для других AWS и сторонних служб безопасности.
  * [Shield](https://aws.amazon.com/shield/): Служба защиты от DDoS-атак.
  * [Single Sign-On](https://aws.amazon.com/single-sign-on/): Сервис централизованного управления доступом AWS или приложения.
  * [ThreatMapper](https://github.com/deepfence/ThreatMapper): Выявление уязвимостей в запущенных контейнерах, образах, хостах и репозиториях.
  * [VPC Flowlog](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html): Журнал сетевого трафика.
  * [WAF](https://aws.amazon.com/waf/): Служба брандмауэра веб-приложений.
* Azure
  * [Application Gateway](https://azure.microsoft.com/en-us/services/application-gateway/): Балансировщик нагрузки L7 с дополнительной функцией WAF.
  * [DDoS Protection](https://azure.microsoft.com/en-us/services/ddos-protection/): Служба защиты от DDoS-атак.
  * [Dedicated HSM](https://azure.microsoft.com/en-us/services/azure-dedicated-hsm/): Cервис HSM.
  * [Key Vault](https://azure.microsoft.com/en-us/services/key-vault/): Cервис KMS.
  * [Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/): Журнал API и сервис, связанный с мониторингом.
  * [Security Center](https://azure.microsoft.com/en-us/services/security-center/): Служба интеграции для других служб безопасности Azure и сторонних поставщиков.
  * [Sentinel](https://azure.microsoft.com/zh-tw/services/azure-sentinel/): Cервис SIEM.
* GCP
  * [Access Transparency](https://cloud.google.com/access-transparency): Журнал прозрачности и контроль GCP.
  * [Apigee Sense](https://cloud.google.com/apigee/api-management/apigee-sense): Мониторинг безопасности API, обнаружение, смягчение последствий.
  * [Armor](https://cloud.google.com/armor): Защита от DDoS и сервис WAF.
  * [Asset Inventory](https://cloud.google.com/asset-inventory): Сервис мониторинга активов.
  * [Assured workloads](https://cloud.google.com/assured-workloads/): Безопасные и совместимые рабочие нагрузки.
  * [Audit Logs](https://cloud.google.com/audit-logs): API журналы.
  * [Binanry Authorization](https://cloud.google.com/binary-authorization/): Сервис бинарной авторизации для контейнеров и безсерверных.
  * [Cloud HSM](https://cloud.google.com/hsm): Cервис HSM.
  * [Cloud IDS](https://cloud.google.com/intrusion-detection-system/): Cервис IDS.
  * [Confidential VM](https://cloud.google.com/compute/confidential-vm/): Шифруйте данные, используемые с виртуальной машиной.
  * [Context-aware Access](https://cloud.google.com/context-aware-access): Включите доступ с нулевым доверием к приложениям и инфраструктуре.
  * [DLP](https://cloud.google.com/dlp): Cервис DLP:
  * [EKM](https://cloud.google.com/ekm): Внешняя служба управления ключами
  * [Identity-Aware Proxy](https://cloud.google.com/iap): Identity-Aware Proxy для защиты внутренней службы.
  * [KMS](https://cloud.google.com/kms): Cервис KMS.
  * [Policy Intelligence](https://cloud.google.com/policy-intelligence): Обнаружение риска, связанного с политикой.
  * [Security Command Center](https://cloud.google.com/security-command-center): Служба интеграции для другой службы безопасности GCP.
  * [Security Scanner](https://cloud.google.com/security-scanner): Сканер безопасности приложений для GAE, GCE, GKE.
  * [Shielded VM](https://cloud.google.com/compute/shielded-vm/): ВМ с безопасной загрузкой и vTPM.
  * [Event Threat Detection](https://cloud.google.com/event-threat-detection): Служба обнаружения угроз.
  * [VPC Service Controls](https://cloud.google.com/vpc-service-controls): Контроль периметра безопасности службы GCP.

# Материалы для чтения
- [AWS](#aws)
- [Azure](#azure)
- [GCP](#gcp)
- [Другие](#Другие)

## AWS
1. [Overiew of AWS Security](https://aws.amazon.com/security/)
2. [AWS-IAM-Privilege-Escalation by RhinoSecurityLabs](https://github.com/RhinoSecurityLabs/AWS-IAM-Privilege-Escalation): Централизованный источник всех методов повышения привилегий AWS IAM.
3. [MITRE ATT&CK Matrices of AWS](https://attack.mitre.org/matrices/enterprise/cloud/aws/)
4. [AWS security workshops](https://github.com/aws-samples/aws-security-workshops)
5. [ThreatModel for Amazon S3](https://github.com/trustoncloud/threatmodel-for-aws-s3): Библиотека всех сценариев атак на Amazon S3 и способов их смягчения с использованием подхода, основанного на оценке рисков.
## Azure
1. [Overiew of Azure Security](https://azure.microsoft.com/en-us/overview/security/)
2. [Azure security fundamentals](https://docs.microsoft.com/en-us/azure/security/fundamentals/)
3. [MicroBurst by NetSPI](https://github.com/NetSPI/MicroBurst): Коллекция скриптов для оценки безопасности Microsoft Azure.
4. [MITRE ATT&CK Matrices of Azure](https://attack.mitre.org/matrices/enterprise/cloud/azure/)
5. [Azure security center workflow automation](https://github.com/Azure/Azure-Security-Center/tree/master/Workflow%20automation)
## GCP
1. [Overiew of GCP Security](https://cloud.google.com/security)
2. [GKE security scenarios demo](https://github.com/GoogleCloudPlatform/gke-security-scenarios-demo)
3. [MITRE ATT&CK Matrices of GCP](https://attack.mitre.org/matrices/enterprise/cloud/gcp/)
4. [Security response automation](https://github.com/GoogleCloudPlatform/security-response-automation)
## Другие
1. [Cloud Security Research by RhinoSecurityLabs](https://github.com/RhinoSecurityLabs/Cloud-Security-Research) 
2. [CSA cloud security guidance v4](https://cloudsecurityalliance.org/artifacts/security-guidance-v4/)
3. [Appsecco provides training](https://github.com/appsecco/breaking-and-pwning-apps-and-servers-aws-azure-training)
4. [Cloud Risk Encyclopedia by Orca Security](https://orca.security/resources/cloud-risk-encyclopedia/): Более 900 задокументированных рисков облачной безопасности с возможностью фильтрации по поставщику облачных услуг, системе соответствия, категории риска и критичности.

# Ресурс
- [AWS](#aws-1)
- [Другие](#others-1)
## AWS
1. [Bucket search by grayhatwarfare](https://buckets.grayhatwarfare.com/)

## Другие
1. [Mapping of On-Premises Security Controls vs. Major Cloud Providers Services](https://www.eventid.net/docs/onprem_to_cloud.asp)

# Большое спасибо за "Amazing Cloud ressources" от 4andersonlin за его потрясающую работу!

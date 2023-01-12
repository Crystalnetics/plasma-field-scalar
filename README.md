# plasma-field-scalar

```
plasma-field-scalar
├── README.md
├── LICENSE
├── docs
│   ├── architecture.md
│   ├── design.md
│   ├── installation.md
│   ├── usage.md
│   ├── troubleshooting.md
│   ├── security_best_practices.md
│   ├── biometric_authentication.md
│   └── regulatory_compliance.md
├── hardware
├── scalar_field_production/
│   ├── waveguides/
│   │   ├── waveguide_1.yaml
│   │   ├── waveguide_2.yaml
│   ├── resonant_cavities/
│   │   ├── resonant_cavity_1.yaml
│   │   ├── resonant_cavity_2.yaml
│   └── antenna_arrays/
│       ├── antenna_array_1.yaml
│       ├── antenna_array_2.yaml
├── plasma_field_production/
│   ├── gas_discharge_tubes/
│   │   ├── gas_discharge_tube_1.yaml
│   │   ├── gas_discharge_tube_2.yaml
│   ├── laser-induced_plasmas/
│   │   ├── laser_induced_plasma_1.yaml
│   │   ├── laser_induced_plasma_2.yaml
│   └── radio-frequency_plasma_generators/
│       ├── radio_frequency_plasma_generator_1.yaml
│       ├── radio_frequency_plasma_generator_2.yaml
├── data_acquisition_systems/
│   ├── data_acquisition_system_1.yaml
│   ├── data_acquisition_system_2.yaml
├── sensors/
│   ├── sensor_1.yaml
│   ├── sensor_2.yaml
└── high-speed_cameras/
│   ├── high_speed_camera_1.yaml
│   ├── high_speed_camera_2.yaml
│   ├── bill_of_materials.csv
├── software api
│   ├── bioinfo_api.py
│   ├── auth_api.py
│   ├── biometric_api.py (added for biometric authentication 
├── microservices
│   ├── edge-service
│   │   ├── edge-service.py
│   │   ├── edge-service_test.py
│   │   ├── requirements.txt
│   │   └── deployment.yaml
│   │   └── README.md
│   └── cloud-service
│       ├── cloud-service.py
│       ├── cloud-service_test.py
│       ├── requirements.txt
│       └── deployment.yaml
│       └── README.md
├── webgui
│   ├── index.html
│   ├── style.css
│   ├── app.js
│   ├── login.js
│   ├── webgui_test.js
│   ├── biometric_authentication.js
│   ├── deployment.yaml
│   ├── images
│   │   ├── image_1.png
│   │   ├── image_2.png
│   │   ├── ...
│   ├── icons
│   │   ├── icon_1.svg
│   │   ├── icon_2.svg
│   │   ├── ...
├── k8s
│   ├── cluster-config
│   ├── istio-config
│   │   ├── istio-ingress.yaml
│   │   ├── istio-egress.yaml
│   │   ├── istio-service-entry.yaml
│   │   └── ...
│   ├── kustomization.yaml
│   ├── monitoring_logging.yaml
│   └── cert-manager-config
│       ├── cert-manager-issuer.yaml
│       └── cert-manager-cluster-issuer.yaml
└── infra
    ├── terraform
    │   ├── main.tf
    │   ├── variables.tf
    │   ├── outputs.tf
    │   └── terraform.tfvars
    ├── ansible
    │    ├── playbook.yml
    │    ├── inventory
    │    └── group_vars
    ├── ci_cd_pipeline
        ├── .travis.yml
        ├── Jenkinsfile
        ├── Jenkinsfile.tests
        ├── Jenkinsfile.build
        └── Jenkinsfile.deploy
```

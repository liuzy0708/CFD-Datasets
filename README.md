# Compound Fault Diagnosis Dataset of Rotating Machinery

![platform](https://user-images.githubusercontent.com/115722686/195636988-4477e226-16f5-4215-8601-febda5109235.png)

## Overview

This repository provides experimental data collected from a realistic large-scale rotating machinery fault diagnosis experimental platform. The dataset aims to facilitate research and development in the field of fault diagnosis for rotating machinery. The experimental setup includes a centrifugal multi-stage impeller blower with various fault conditions simulated in different data folds.

## Description

The experimental data is collected from a realistic large-scale rotating machinery fault diagnosis experimental platform. The test rig is utilized in Guangdong Province Key Laboratory for petrochemical equipment fault diagnosis. Initial vibration signals are obtained by sensors installed on the gearbox with a US CTC accelerometer mounted vertically on the gearbox. In detail, it is a centrifugal multi-stage impeller blower with crucial components such as a three-phase induction motor, gearbox, bearing, load, and shaft. In addition, gear wheels and pinions are engaged and abrade mutually inside the gearbox.

## Data Folds Details:

- **F0**: Normal bearing; Normal gearwheel
- **F1**: Normal bearing; Defective gearwheel
- **F2**: Defective inner-ring of bearing; Normal gearwheel
- **F3**: Defective inner-ring of bearing; Defective gearwheel
- **F4**: Defective outer-ring of bearing; Normal gearwheel
- **F5**: Defective outer-ring of bearing; Defective gearwheel
- **F6**: Bearing with the absence of balls; Normal gearwheel
- **F7**: Bearing with the absence of balls; Defective gearwheel

## Utilized Test Rig:

![photo](https://user-images.githubusercontent.com/115722686/195637306-ac88470b-9b61-45de-89aa-a94cfed8cfa8.png)

## Parameters Description:

- **chip**: Data collection channel
- **wave**: Collected vibration signal

## Installation

To utilize this dataset, simply clone the repository:

```bash
git clone https://github.com/your_username/your_repository.git
cd your_repository
```

## Usage

Explore the dataset for fault diagnosis research and experimentation. Analyze vibration signals under different fault conditions to develop and evaluate fault diagnosis algorithms and techniques.

## Citation

If you use this dataset in your research, please consider citing:

```
@ARTICLE{10292791,
  author={Liu, Zeyi and Zhang, Jingfei and He, Xiao},
  journal={IEEE Transactions on Automation Science and Engineering}, 
  title={A Discrimination-Guided Active Learning Method Based on Marginal Representations for Industrial Compound Fault Diagnosis}, 
  year={2023},
  volume={},
  number={},
  pages={1-12},
  doi={10.1109/TASE.2023.3325271}}

@ARTICLE{9869794,
  author={Liu, Zeyi and Zhang, Jingfei and He, Xiao and Zhang, Qinghua and Sun, Guoxi and Zhou, Donghua},
  journal={IEEE Transactions on Control Systems Technology}, 
  title={Fault Diagnosis of Rotating Machinery With Limited Expert Interaction: A Multicriteria Active Learning Approach Based on Broad Learning System}, 
  year={2023},
  volume={31},
  number={2},
  pages={953-960},
  doi={10.1109/TCST.2022.3200214}}
```

## Contributing

Contributions to improve the dataset, such as additional fault conditions or data annotations, are welcome. Please open an issue or submit a pull request with your suggestions or improvements.

## License

This dataset is provided under the [license](LICENSE) included in the repository.

## Contact

For any inquiries or questions regarding the dataset, please contact [liuzy21@mails.tsinghua.edu.cn](mailto:liuzy21@mails.tsinghua.edu.cn).

## Acknowledgments

The dataset is supported by the Guangdong Province Key Laboratory for Petrochemical Equipment Fault Diagnosis.
We extend our sincere gratitude to our THUFDD Group, led by Prof. Xiao He and Prof. Donghua Zhou, for their invaluable support and contributions to the development of this scheme.

## Views
![](http://profile-counter.glitch.me/CFD-Datasets/count.svg)

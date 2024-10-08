# NeuralWorks
NeuralWorks is a comprehensive toolkit for building, training, and running custom neural network models, offering an intuitive console-based interface for image classification and processing. Very beginner friendly step-by-step guidance.

The ultimate goal is to make the system unbreakable, to allow more people without ML background to get familiar with architectire design and build their own models. Ideally, I would love this to expand to LLMs and more advanced model creation.

Enjoy!

# Features

- Classifier builder.
- Image processing (Super-resolution, down-sampling, mapping).
- Interactive custom architecture builder with guidance.
- Backup & Restore system.
- Advanced data management.

# Requirements

  - Python >= 3.10.11
  - PyTorch (torch) >= 1.12.0
  - Torchvision (torchvision) >= 0.13.0
  - PIL (Pillow) >= 9.2.0

# Try NeuralWorks
To initialise your environment, download 'requirements.txt' and run:

  - pip install -r requirements.txt

Download the 'nw.py' script or copy the code into your favourite IDE.

# Future Updates
Version 1.0.1:

- CUDA acceleration support with additional environment handling.
- Support for all resolutions, not just square images.
- PolyInfo Selection Library integration.
- Logging/buffer diagnostic tracing system.
- Information menu, with feedback options.
- Improved edge case handling.
- Bug fixes applied mentioned in 1.0.0.

Release Date: soon™

Version 1.0.2:

- Precision/sensitivity and PSNR/SSIM metrics for classification and image processing.
- Analytic data collection (optional): model architecture, metrics, system performance, etc.
- Additional bug fixes and toughened error/edge case handling system.
- NeuralWorksCustom Framework Integration to provide an alternative to PyTorch. (https://github.com/OguzhanCOG/NWCustom/)
- Input sanitisation to mitigate risks associated with eval() function usage.
- User authentication and authorisation for multi-user environments.
- Encryption of sensitive data stored in the SQLite database.
- Secure error handling to prevent information leakage with proper exception management and user-friendly error messages
- Improved input validation for all user inputs to prevent unexpected behavior.
- Performance optimisations for handling large datasets and complex models.
- GUI implementation option for users who prefer graphical interfaces.
- Refactored system environment and source code.

More planned for the future.

Release Date: N/A

# Contributing
Contributions to NeuralWorks are welcome! Please feel free to submit pull requests or open issues for bugs, feature requests, or improvements.

Feedback? motions.07-busses@icloud.com

# License
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><span property="dct:title">NeuralWorks Version 1.0.0</span> by <span property="cc:attributionName">Oguzhan Cagirir</span> is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt=""></a></p>

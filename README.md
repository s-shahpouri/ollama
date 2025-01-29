# SERA: AI Assistant for Medical Inquiries

SERA is an AI-powered assistant designed to help users with medical inquiries in both English and Dutch. It is integrated with a hospital setting in Groningen, providing assistance with tasks such as appointment booking and general medical questions.

## Features

- **Multilingual support**: SERA can communicate in both English and Dutch.
- **Medical Assistance**: Provides information related to healthcare, appointments, and medical procedures.
- **Customizable Model**: SERA is built using the `deepseek-r1:8b` model, modified through a custom `Modelfile`.

## Requirements

- Python 3.x
- ollama (for AI model handling)
- Requests (for interacting with local API)

## Installation

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/your-username/my-repo.git](https://github.com/s-shahpouri/ollama.git)
Install the required dependencies:
Start the ollama server:

   ```bash
   ollama serve
Run the model: To interact with SERA, run:

   ```bash
   ollama run SERA
How It Works
Modelfile Setup: The Modelfile contains the necessary configuration to create and customize the SERA model.

FROM: Specifies the base model (deepseek-r1:8b).
PARAMETER:  temperature = 1.
SYSTEM: Defines SERA's role and purpose in the hospital setting.


Contribution
Feel free to fork this repository and submit pull requests. If you have any suggestions or improvements, open an issue!

License
This project is licensed under the MIT License - see the LICENSE file for details.







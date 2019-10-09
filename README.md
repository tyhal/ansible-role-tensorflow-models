# ansible-role-tensorflow-models

 Deploy "Models and examples built with TensorFlow"

## Install

```bash
	ansible-galaxy install tyhal.tensorflow-models
```

## Usage

Then you can use this with:

```yaml
- hosts: all
  become: yes
  roles:
    - { role: tyhal.tensorflow-models }
```

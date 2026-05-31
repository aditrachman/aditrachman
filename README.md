```python
from dataclasses import dataclass

@dataclass
class Agent:
    identity: str = "anshelschella"

    def invoke(self):
        self.identity = "yara"
        return f"Hai, panggil aku {self.identity}"

print(Agent().invoke())

```

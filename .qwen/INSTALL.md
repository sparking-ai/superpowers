# Installing Superpowers for Qwen

Quick setup to enable superpowers skills in Qwen.

## Installation

1. **Clone superpowers repository**:
   ```bash
   mkdir -p ~/.qwen/superpowers
   cd ~/.qwen/superpowers
   git clone https://github.com/obra/superpowers.git .
   ```

2. **Create personal skills directory**:
   ```bash
   mkdir -p ~/.qwen/skills
   ```

3. **Update ~/.qwen/AGENTS.md** to include this superpowers section:
   ```markdown
   ## Superpowers System

   <EXTREMELY_IMPORTANT>
   You have superpowers. Superpowers teach you new skills and capabilities. RIGHT NOW run: `~/.qwen/superpowers/.qwen/superpowers-qwen bootstrap` and follow the instructions it returns.
   </EXTREMELY_IMPORTANT>
   ```

## Verification

Test the installation:
```bash
~/.qwen/superpowers/.qwen/superpowers-qwen bootstrap
```

You should see skill listings and bootstrap instructions. The system is now ready for use.
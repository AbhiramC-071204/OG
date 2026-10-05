python -m pip install --upgrade pip
python -m pip install streamlit

python -m streamlit --version

if Fix pnpm
Your error:
EPERM: operation not permitted, open 'C:\Program Files\nodejs\pnpx'

means Corepack doesn't have permission to write inside C:\Program Files\nodejs.
First check Node:
node --version
npm --version
corepack --version

npm install -g pnpm
pnpm --version

pnpm install --frozen-lockfile
pnpm dev

npm install -g pnpm
pnpm install
pnpm --version
pnpm dev

Then open the URL shown in the terminal, usually:
http://localhost:3000





resourse  repo : https://github.com/gireeshkumarreddy/pk


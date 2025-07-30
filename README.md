# Blazor Tailwind Template

A .NET 9 Blazor Server template with Tailwind CSS v4.

## Installation

```bash
git clone https://github.com/francis-j/Blazor.Tailwind.Template.git
cd Blazor.Tailwind.Template
dotnet new install .
dotnet new blazortailwind -n MyProject
```

## Setup

1. **Install dependencies:**
```bash
dotnet restore
npm install
```

2. **Generate Tailwind CSS:**
```bash
npx @tailwindcss/cli -i ./wwwroot/css/main.css -o ./wwwroot/css/app.css --watch
```

3. **Run application:**
```bash
dotnet run
```
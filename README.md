````markdown
# 🏥 Medical Appointment Management System

Sistema moderno para gerenciamento de **consultas médicas**, oferecendo acesso personalizado para **pacientes**, **médicos** e **administradores**.  
Desenvolvido em **React + TypeScript**, com foco em escalabilidade, segurança e experiência do usuário.

---

## 🚀 Funcionalidades Principais
- 🔐 **Autenticação**: login, registro e gerenciamento de perfis.  
- 🏠 **Dashboards**:
  - Paciente: agendamento e acompanhamento de consultas.  
  - Médico: gestão de agenda e consultas.  
  - Administrador: controle de usuários e permissões.  
- 📅 **Agendamentos**: criar, editar e cancelar consultas.  
- 👤 **Perfil**: atualização de informações pessoais.  

---
````
## 📂 Estrutura
```

screens/
├── AdminDashboardScreen.tsx
├── CreateAppointmentScreen.tsx
├── DoctorDashboardScreen.tsx
├── HomeScreen/
├── HomeScreen.tsx
├── LoginScreen.tsx
├── PatientDashboardScreen.tsx
├── ProfileScreen.tsx
├── RegisterScreen.tsx
└── UserManagementScreen.tsx

````
## 🛠️ Tecnologias
- **React** + **TypeScript**  
- **React Router / Navigation** (rotas)  
- **Context API / Redux** (estado global)  
- **TailwindCSS / Styled Components** (UI responsiva)  
- **Axios / Fetch API** (requisições HTTP)  
- **ESLint + Prettier** (boas práticas e padronização)  
````


## 📦 Instalação
```bash
# Clone o repositório
git clone https://github.com/Inorganicelf/Marcacao_De_Consultas.git

# Acesse a pasta
cd marcacaoDeConsultasMedicas

# Instale as dependências
npm install

# Inicie o projeto
npm start
````

O sistema ficará disponível em `http://localhost:3000/`.

---

## 🧪 Testes

```bash
npm test
```

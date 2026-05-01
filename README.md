# Conference Management System

🇬🇧 **English:**
A robust application designed to streamline the organization and management of academic and professional conferences. Developed with C# and .NET, the system allows administrators to schedule sessions, manage speaker profiles, and handle attendee registrations. It provides a clean, user-friendly interface to ensure events run smoothly from planning to execution.

🇹🇷 **Türkçe:**
Akademik ve profesyonel kongrelerin organizasyon sürecini kolaylaştırmak amacıyla geliştirilmiş güçlü bir yönetim sistemidir. C# ve .NET kullanılarak inşa edilen bu sistem; yöneticilerin oturum planlaması yapmasına, konuşmacı profillerini yönetmesine ve katılımcı kayıtlarını takip etmesine olanak tanır. Etkinliklerin planlama aşamasından tamamlanmasına kadar sorunsuz ilerlemesini sağlayan, kullanıcı dostu bir arayüze sahiptir.

## Features / Özellikler

- **Session Scheduling:** Create and organize multiple event tracks and time slots.
- **Speaker Management:** Maintain detailed profiles for presenters and keynote speakers.
- **Attendee Registration:** Secure ticket booking and attendee tracking.
- **Dashboard Overview:** Quick insights into event capacity and upcoming schedules.

## Technologies Used / Kullanılan Teknolojiler

- **C# / .NET 8.0**
- **Entity Framework Core**
- **SQL Server**

## Setup and Execution / Kurulum ve Çalıştırma

1. Clone the repository / Depoyu klonlayın.
2. Ensure you have the .NET SDK installed / .NET SDK'nın kurulu olduğundan emin olun.
3. Apply database migrations / Veritabanı migrasyonlarını uygulayın:
   ```bash
   dotnet ef database update
   ```
4. Run the project / Projeyi çalıştırın:
   ```bash
   dotnet run
   ```

# Схема сети и конфигурации

## Таблица IP-адресации

| Устройство | Интерфейс / Назначение | IP-адрес / Маска | Шлюз |
|------------|------------------------|------------------|------|
| **HQ-RTR** | к hq-srv | 192.168.100.1/26 | 172.16.1.1 |
| | к hq-cli | 192.168.200.1/28 | |
| | к isp | 172.16.1.2/28 | |
| | gre к br-rtr | 10.255.255.1/30 | |
| **BR-RTR** | к br-srv | 192.168.0.1/27 | 172.16.2.1 |
| | к isp | 172.16.2.2/28 | |
| | gre к hq-rtr | 10.255.255.2/30 | |
| **HQ-SRV** | к hq-rtr | 192.168.100.2/26 | 192.168.100.1 |
| **BR-SRV** | к br-rtr | 192.168.0.2/27 | 192.168.0.1 |
| **HQ-CLI** | к hq-rtr | 192.168.200.2/28 | 192.168.200.1 |
| **ISP** | к hq-rtr | 172.16.1.1/28 | |
| | к br-rtr | 172.16.2.1/28 | |

## ISP

<p align="center">
  <img src="https://github.com/user-attachments/assets/5b73e70e-cae9-429c-a0e6-a63f7a40d77f" alt="ISP config 1">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/590f9cf1-13f2-408f-bf69-a56d1191169d" alt="ISP config 2">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/6fd8ddd7-9361-4d14-83d4-64a2b4a68508" alt="ISP config 3">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/2f27e917-9866-46c3-9aa1-98843681aa5b" alt="ISP config 4">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/df92fd8c-1e76-4a7b-b4e0-be128dbcba89" alt="ISP config 5">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/5da89a20-3188-40a1-af64-e84fb84be958" alt="ISP config 6">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/23b24048-a195-433b-a718-7eb0beb463ef" alt="ISP config 7">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d5e2061a-2137-496d-91a6-facc0405a9d8" alt="ISP config 8">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/954fc0f0-2a61-40ab-9498-68df6a40418d" alt="ISP config 9">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/85ff3d39-efff-4a2a-9559-d009e0527a57" alt="ISP config 10">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/de164060-28a7-4587-a9df-652635623d41" alt="ISP config 11">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c55f26c1-1a07-4b6e-a33a-df192255ae75" alt="ISP config 12">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/04e50a52-d32a-42ec-9688-6b798d98bc77" alt="ISP config 13">
</p>

---

## HQ-RTR

<p align="center">
  <img src="https://github.com/user-attachments/assets/42c085ec-25a7-4bc3-b472-9747a65fa591" alt="HQ-RTR config 1">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ebd9d766-f7e0-43a1-9420-d026e8c9431f" alt="HQ-RTR config 2">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/99556726-1de7-4814-964d-cedbe6d92d5e" alt="HQ-RTR config 3">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ac516c90-754f-40ea-8f6e-472a3a2fbb1c" alt="HQ-RTR config 4">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/626d1d34-f323-401b-976b-38aaa5a524ec" alt="HQ-RTR config 5">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/1a4c2c99-7eb2-44bb-b0a3-fd6f1e136c93" alt="HQ-RTR config 6">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/7895369d-2683-494f-a9de-672f7797822f" alt="HQ-RTR config 7">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/8d50df4c-cd6a-4524-82d2-5ec0dc14ddcd" alt="HQ-RTR config 8">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f1f9645a-835a-4ab4-ac52-2f9a250e3fc5" alt="HQ-RTR config 9">
</p>

> **Примечание:** да опечатка 157

<p align="center">
  <img src="https://github.com/user-attachments/assets/9e58cfdd-e21f-4827-8e87-0f4c2ebed79b" alt="HQ-RTR config 10">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/fb9a4a9c-220e-4b6f-8fa6-6b9ac29c7ec5" alt="HQ-RTR config 11">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/08f57f60-d689-44e6-b4e9-49cb9b4f2288" alt="HQ-RTR config 12">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ba348c84-ea09-40ad-bc03-16f3b50717d9" alt="HQ-RTR config 13">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/73e8d90a-eb2d-4e82-b57f-f6fe437c5abd" alt="HQ-RTR config 14">
</p>

> **Примечание:** поменять номера, ens33.x → ens192, ens37.x → ens224.x

<p align="center">
  <img src="https://github.com/user-attachments/assets/4151062f-9ba8-49a2-8079-472eb769e9ed" alt="HQ-RTR config 15">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/57c15b2b-080e-4913-a956-115fa49f29bd" alt="HQ-RTR config 16">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b1b9fed9-bbd6-461a-9308-4e49a47cb17f" alt="HQ-RTR config 17">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0fd24f5e-2569-4e55-9096-dbc68f92059b" alt="HQ-RTR config 18">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/94ea9351-4762-424c-9b8f-b4203011101f" alt="HQ-RTR config 19">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/5374cbe7-6558-4928-9e32-1ea3a1878704" alt="HQ-RTR config 20">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e5ff7716-d7c0-44f4-ba47-050edc58ede5" alt="HQ-RTR config 21">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/1f47b537-02ee-49a3-b4db-0fb8895667ef" alt="HQ-RTR config 22">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/65c9e0b2-b896-41a1-90a2-c2a4d994c8a0" alt="HQ-RTR config 23">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/59a3290d-0afc-487b-be8f-b239c1bd4763" alt="HQ-RTR config 24">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d6190a99-7fc0-472d-a2e2-698920cdb4fc" alt="HQ-RTR config 25">
</p>

### tun0

<p align="center">
  <img src="https://github.com/user-attachments/assets/d91e60eb-b490-4359-b104-af87a7b53edb" alt="HQ-RTR tun0 1">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/98506e2d-f303-4109-bfb0-71a721673e05" alt="HQ-RTR tun0 2">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d9ca4965-1174-482f-8411-6ab945e5f1bb" alt="HQ-RTR tun0 3">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/5a1f802a-7547-4f68-96f6-b12105b91f16" alt="HQ-RTR tun0 4">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/867b13b0-b0f3-444d-a901-4670d671084c" alt="HQ-RTR tun0 5">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/8ba97f95-f248-4c43-8d11-8373d352ea3a" alt="HQ-RTR tun0 6">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/76581523-a11d-45eb-8e26-69d8177b9ba5" alt="HQ-RTR tun0 7">
</p>

> **Примечание:** или через systemctl ...

---

## BR-RTR

<p align="center">
  <img src="https://github.com/user-attachments/assets/ce1d866c-0e63-49ad-b8ac-b07cc7b56fff" alt="BR-RTR config 1">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b8614edf-3f13-4866-a4e2-1b72d92daf54" alt="BR-RTR config 2">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/04c9b71a-bf6d-4e7d-b07e-5672326f593e" alt="BR-RTR config 3">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/fa18a101-2e94-43a7-97bd-5047eebb96ea" alt="BR-RTR config 4">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b055ffc9-eeb9-4644-bbc1-999307394da7" alt="BR-RTR config 5">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f84d0942-3429-45f9-803e-46b3a20486ff" alt="BR-RTR config 6">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/20e82b63-9033-4a87-8ca0-a78f4a808254" alt="BR-RTR config 7">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cf261b37-913c-4ee9-923e-08dd1a9ebd3b" alt="BR-RTR config 8">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/96cc0f72-ec20-4b7f-907e-d31ec6dd6f8a" alt="BR-RTR config 9">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e7f279ec-1bb2-44ac-af08-9192383b8286" alt="BR-RTR config 10">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/00a47701-47c6-4071-b43c-5371d3199464" alt="BR-RTR config 11">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/aeb775bd-d09c-49c1-9066-178506590a36" alt="BR-RTR config 12">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/67352312-b04b-468d-9103-13b8fe70abf3" alt="BR-RTR config 13">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9e53deb0-0040-46b8-8bec-30e76756cb25" alt="BR-RTR config 14">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a4a64c59-9790-4998-b223-7441625b9bf1" alt="BR-RTR config 15">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d13e98f7-56d2-4ca3-a463-5c43f1285f80" alt="BR-RTR config 16">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/005224ed-f792-4fde-b434-645eaf908b33" alt="BR-RTR config 17">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0dd296a7-f150-427e-929c-d62d038153e7" alt="BR-RTR config 18">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/51bde52c-4562-4ce6-a63f-aa9e17d73677" alt="BR-RTR config 19">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e9daf8a0-0853-4bbe-88b0-31226c1d7ff2" alt="BR-RTR config 20">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/500e5068-cccd-42a5-a500-afc1139e2ee8" alt="BR-RTR config 21">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/1a5b54f1-2c33-45fb-b717-170e0efb1a7b" alt="BR-RTR config 22">
</p>

### tun0

<p align="center">
  <img src="https://github.com/user-attachments/assets/66119794-bc9c-4b61-823d-22052eb3f262" alt="BR-RTR tun0 1">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/17316b77-2444-4a65-bda4-23bea4530ecd" alt="BR-RTR tun0 2">
</p>

---

## HQ-SRV

<p align="center">
  <img src="https://github.com/user-attachments/assets/572da7aa-e70f-48b7-b17b-7df8aca96765" alt="HQ-SRV config 1">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/33fec831-f68f-4c1f-b378-59306581f452" alt="HQ-SRV config 2">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/6aef802c-6878-4026-a015-9d47a17df6c3" alt="HQ-SRV config 3">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f74111c0-c99f-4a33-889f-f8b34663b583" alt="HQ-SRV config 4">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/2e4f560a-9493-4ac7-842c-5ee0ddbcd7d5" alt="HQ-SRV config 5">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/044dbb72-2819-41f5-b307-76c9b4735ffd" alt="HQ-SRV config 6">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/59724c7d-711d-4865-93a8-e1e22b0d4bd5" alt="HQ-SRV config 7">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c1f966e6-3448-476f-9a44-cb38150893d1" alt="HQ-SRV config 8">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cf74ea8d-6107-4315-8e94-0b9301f46327" alt="HQ-SRV config 9">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/506fadc2-34f9-49f2-a3c6-954902922da8" alt="HQ-SRV config 10">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4214b8fe-e26c-4fcb-a47f-b22ce91f3a86" alt="HQ-SRV config 11">
</p>

> **Примечание:** написать под directory

<p align="center">
  <img src="https://github.com/user-attachments/assets/30bbef8a-feab-4923-bfc1-aaf91e59a153" alt="HQ-SRV config 12">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d908ab60-56b3-4b2f-b9c7-0cd7036c3f11" alt="HQ-SRV config 13">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b3060f8c-5e7c-4891-a821-fe4d5048d7eb" alt="HQ-SRV config 14">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d61c5c24-e8c1-477b-b37e-8ce348e7eab5" alt="HQ-SRV config 15">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bfed8851-603a-4ffd-b639-db46c9c59971" alt="HQ-SRV config 16">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/668cd9e7-a564-46ff-a33e-ef50d2bcc238" alt="HQ-SRV config 17">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9f04e27d-2863-4a1f-ade3-7c6e5df17154" alt="HQ-SRV config 18">
</p>

> **Примечание:** service bind9 restart

---

## BR-SRV

<p align="center">
  <img src="https://github.com/user-attachments/assets/56a170f7-5d4d-43e9-9a8e-23a25aaa700d" alt="BR-SRV config 1">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/64e3df75-5f66-4f86-b7fb-d375e37ca224" alt="BR-SRV config 2">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/97274516-8c2a-4a3f-aea5-59f8b5fddef6" alt="BR-SRV config 3">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/5199b7cb-e30d-43f9-aefc-b136fa351899" alt="BR-SRV config 4">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/75eb537e-f028-4ff4-9f01-3ad5fbb9eefb" alt="BR-SRV config 5">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/872a3924-8527-4363-9f1f-40056306d36e" alt="BR-SRV config 6">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f86cf39e-9c86-407b-9bd9-31e17ac7d9de" alt="BR-SRV config 7">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/04993960-e81e-416f-b646-fc1de842ae17" alt="BR-SRV config 8">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a222dba1-af21-4a94-ac38-9e84d8d8cb29" alt="BR-SRV config 9">
</p>

> **Примечание:** с BR-RTR

<p align="center">
  <img src="https://github.com/user-attachments/assets/3b474a6a-2abd-4fc8-979c-731011eda4bc" alt="BR-SRV config 10">
</p>

---

## HQ-CLI

<p align="center">
  <em>Изображения для HQ-CLI не предоставлены</em>
</p>

# farmacia-de-turno-hoy-baradero
Consulta la farmacia que está de turno hoy en Baradero. Encuentra dirección, teléfono, y mapa actualizado para el servicio de guardia 24 horas

## Publicación

Publicado en

Google Analytics:  
  

## Cuenta de correo

Publicidad Farmacias Turno
[publicidad.farmacias.turno@gmail.com](mailto:publicidad.farmacias.turno@gmail.com)

## Base de farmacias
``
const PHARMACIES = [
  { id: '1', name: 'Farmacia Amartino', address: "J. O'Roarke 2408", phone: '(03329) 480263' },
  { id: '2', name: 'Farmacia Anchorena', address: 'Bulnes 601', phone: '(03329) 480233' },
  { id: '3', name: 'Farmacia Boedo', address: 'Sta. M. de Oro 811', phone: '(03329) 485671' },
  { id: '4', name: 'Farmacia Bolaños', address: 'Lino Piñeiro 279', phone: '(03329) 482403' },
  { id: '5', name: 'Farmacia Braillard', address: 'Mariano Moreno 1239', phone: '(03329) 486879' },
  { id: '6', name: 'Farmacia Chervaz', address: 'Carrasco 144', phone: '(03329) 484982' },
  { id: '7', name: 'Farmacia Daubian', address: 'Aráoz 1101', phone: '(03329) 483323' },
  { id: '8', name: 'Farmacia Del Pueblo', address: 'Anchorena 1101', phone: '(03329) 480165' },
  { id: '9', name: 'Farmacia Del Varadero', address: 'San Martín 1701', phone: '(03329) 480324' },
  { id: '10', name: 'Farmacia Italiana', address: 'Sta. M. de Oro 481', phone: '(03329) 480112' },
  { id: '11', name: 'Farmacia La Fe', address: 'Gorriti 1401', phone: '(03329) 484190' },
  { id: '12', name: 'Farmacia La Popular', address: 'Sáenz 1300', phone: '(03329) 480316' },
  { id: '13', name: 'Farmacia Musante', address: 'René Simón 1280', phone: '(03329) 482615' },
  { id: '14', name: 'Farmacia Petruzzelli', address: 'San Martín 2125', phone: '(03329) 480577' },
  { id: '15', name: 'Farmacia Silvano', address: 'Anchorena 1150', phone: '(03329) 483907' }
];
``


## Calendario de turnos
``
const SCHEDULE_DAYS = [
  { date: '2026-04-01', pharmacyId: '15' },
  { date: '2026-04-02', pharmacyId: '5' },
  { date: '2026-04-03', pharmacyId: '3' },
  { date: '2026-04-04', pharmacyId: '4' },
  { date: '2026-04-05', pharmacyId: '9' },
  { date: '2026-04-06', pharmacyId: '12' },
  { date: '2026-04-07', pharmacyId: '11' },
  { date: '2026-04-08', pharmacyId: '5' },
  { date: '2026-04-09', pharmacyId: '8' },
  { date: '2026-04-10', pharmacyId: '3' },
  { date: '2026-04-11', pharmacyId: '10' },
  { date: '2026-04-12', pharmacyId: '7' },
  { date: '2026-04-13', pharmacyId: '1' },
  { date: '2026-04-14', pharmacyId: '6' },
  { date: '2026-04-15', pharmacyId: '5' },
  { date: '2026-04-16', pharmacyId: '15' },
  { date: '2026-04-17', pharmacyId: '5' },
  { date: '2026-04-18', pharmacyId: '3' },
  { date: '2026-04-19', pharmacyId: '4' },
  { date: '2026-04-20', pharmacyId: '9' },
  { date: '2026-04-21', pharmacyId: '12' },
  { date: '2026-04-22', pharmacyId: '11' },
  { date: '2026-04-23', pharmacyId: '5' },
  { date: '2026-04-24', pharmacyId: '8' },
  { date: '2026-04-25', pharmacyId: '3' },
  { date: '2026-04-26', pharmacyId: '10' },
  { date: '2026-04-27', pharmacyId: '7' },
  { date: '2026-04-28', pharmacyId: '1' },
  { date: '2026-04-29', pharmacyId: '6' },
  { date: '2026-04-30', pharmacyId: '5' }
];
``

/* === DATA: cursos y prerrequisitos =============================== */
const cursos = [
  /* Semestre 1 */
  { id:'OBMA_A001', nombre:'Fundamentos de la Matronería', cod:'OBMA A001', sem:1, req:[] },
  { id:'OBMA_A002', nombre:'Salud Mental en el Curso de la Vida', cod:'OBMA A002', sem:1, req:[] },
  { id:'DBIO_1091', nombre:'Biología Celular', cod:'DBIO 1091', sem:1, req:[] },
  { id:'DMOR_003', nombre:'Morfología Básica', cod:'DMOR 003', sem:1, req:[] },
  { id:'DQUI_1050', nombre:'Química General y Orgánica', cod:'DQUI 1050', sem:1, req:[] },
  { id:'FORI_0001', nombre:'Antropología', cod:'FORI 0001', sem:1, req:[] },

  /* Semestre 2 */
  { id:'OBMA_B001', nombre:'Anatomía Aplicada a la Gineco‑Obstetricia', cod:'OBMA B001', sem:2, req:['DMOR_003'] },
  { id:'OBMA_B002', nombre:'Educación, Salud y Medio Ambiente', cod:'OBMA B002', sem:2, req:[] },
  { id:'DMOR_0022', nombre:'Integrado Fisio‑Fisiopato I', cod:'DMOR 0022', sem:2, req:['DBIO_1091'] },
  { id:'DMOR_0028', nombre:'Histoembriología', cod:'DMOR 0028', sem:2, req:['DBIO_1091'] },
  { id:'DBIO_1092', nombre:'Bioquímica General', cod:'DBIO 1092', sem:2, req:['DQUI_1050'] },
  { id:'FACU_0004', nombre:'Salud Digital', cod:'FACU 0004', sem:2, req:[] },

  /* Semestre 3 */
  { id:'OBMA_C001', nombre:'Proceso de Atención en Matronería', cod:'OBMA C001', sem:3, req:['OBMA_B001'] },
  { id:'DCEX_0015', nombre:'Bioestadística y Salud', cod:'DCEX 0015', sem:3, req:[] },
  { id:'DMOR_0023', nombre:'Integrado Fisio‑Fisiopato II', cod:'DMOR 0023', sem:3, req:['DMOR_0022'] },
  { id:'DBIO_1093', nombre:'Microbiología Médica', cod:'DBIO 1093', sem:3, req:['DBIO_1092'] },
  { id:'DMOR_0027', nombre:'Embriología y Genética', cod:'DMOR 0027', sem:3, req:['DMOR_0028'] },

  /* Semestre 4 */
  { id:'OBMA_D001', nombre:'Fisiología Obstétrica y Neonatal', cod:'OBMA D001', sem:4, req:['DMOR_0023'] },
  { id:'OBMA_D002', nombre:'Fisiología Ginecológica y Sexual', cod:'OBMA D002', sem:4, req:['DBIO_1093','DMOR_0022'] },
  { id:'DSPU_0012', nombre:'Salud Poblacional', cod:'DSPU 0012', sem:4, req:[] },
  { id:'DBIO_1098', nombre:'Farmacología General', cod:'DBIO 1098', sem:4, req:['DMOR_0022'] },
  { id:'FORI_0002', nombre:'Ética', cod:'FORI 0002', sem:4, req:['FORI_0001'] },
  { id:'OBMA_D003', nombre:'Hito Evaluativo Integrativo', cod:'OBMA D003', sem:4,
    req:['OBMA_C001','DMOR_0023','DBIO_1093','DMOR_0027'] },  /* simplif. */

  /* Semestre 5 */
  { id:'OBMA_E001', nombre:'PAM Médico Quirúrgico', cod:'OBMA E001', sem:5,
    req:['OBMA_C001','DBIO_1093'] },
  { id:'OBMA_E002', nombre:'Patología Obstétrica y Neonatal', cod:'OBMA E002', sem:5,
    req:['OBMA_D001','DBIO_1098'] },
  { id:'OBMA_E003', nombre:'Patología Ginecológica', cod:'OBMA E003', sem:5,
    req:['OBMA_D002','DBIO_1098'] },
  { id:'DSPU_0014', nombre:'Epidemiología', cod:'DSPU 0014', sem:5, req:['DSPU_0012'] },
  { id:'FORI_0003', nombre:'Persona y Sociedad', cod:'FORI 0003', sem:5, req:['FORI_0002'] },

  /* Semestre 6 */
  { id:'OBMA_F001', nombre:'Salud Familiar y Comunitaria', cod:'OBMA F001', sem:6, req:[] },
  { id:'OBMA_F002', nombre:'Gestión y Calidad en Salud', cod:'OBMA F002', sem:6, req:[] },
  { id:'OBMA_F003', nombre:'Consejería en Salud Sexual', cod:'OBMA F003', sem:6, req:['OBMA_E003'] },
  { id:'OBMA_F004', nombre:'Salud Reproductiva y Gerontológica', cod:'OBMA F004', sem:6, req:['OBMA_E003'] },
  { id:'DSPU_0011', nombre:'Metodología de la Investigación', cod:'DSPU 0011', sem:6, req:[] },
  { id:'ELECFORI01', nombre:'Electivo I (Formación Integral)', cod:'ELECFORI01', sem:6, req:[] },

  /* Semestre 7 */
  { id:'OBMA_G001', nombre:'Matronería en Atención Primaria', cod:'OBMA G001', sem:7,
    req:['OBMA_F004','OBMA_E002'] },
  { id:'OBMA_G002', nombre:'Integrado Perinatal y Ginecológico', cod:'OBMA G002', sem:7,
    req:['OBMA_E002','OBMA_F003'] },
  { id:'OBMA_G003', nombre:'Medicina Legal y Matronería', cod:'OBMA G003', sem:7, req:[] },
  { id:'FACU_0005', nombre:'Salud Basada en la Evidencia', cod:'FACU 0005', sem:7, req:[] },
  { id:'DEBI_0001', nombre:'Bioética', cod:'DEBI 0001', sem:7, req:[] },
  { id:'ELECFORI02', nombre:'Electivo II (Formación Integral)', cod:'ELECFORI02', sem:7, req:[] },

  /* Semestre 8 */
  { id:'OBMA_H001', nombre:'Gestión Clínica y Atención Comunitaria', cod:'OBMA H001', sem:8, req:['OBMA_G001'] },
  { id:'OBMA_H002', nombre:'Gestión Clínica Obstétrica y Neonatal', cod:'OBMA H002', sem:8, req:['OBMA_G002'] },
  { id:'OBMA_H003', nombre:'Gestión Clínica Perinatal y Ginecológica', cod:'OBMA H003', sem:8, req:['OBMA_G002'] },
  { id:'OBMA_H004', nombre:'Proyecto de Investigación Interdisciplinaria', cod:'OBMA H004', sem:8, req:['FACU_0005'] },
  { id:'ELECFORI03', nombre:'Electivo III (Formación Integral)', cod:'ELECFORI03', sem:8, req:[] },
  { id:'OBMA_H005', nombre:'Hito Evaluativo Integrativo Interprofesional', cod:'OBMA H005', sem:8,
    req:['OBMA_F001','OBMA_G002'] },

  /* Semestre 9 */
  { id:'OBMA_I001', nombre:'Internado de Especialidades', cod:'OBMA I001', sem:9,
    req:['OBMA_G002','OBMA_H003'] },
  { id:'OBMA_I002', nombre:'Internado de Salud Familiar', cod:'OBMA I002', sem:9,
    req:['OBMA_G002','OBMA_H001'] },
  { id:'ELCDGEE03', nombre:'Gestión de Carrera y Desarrollo Profesional', cod:'ELCDGEE03', sem:9, req:[] },

  /* Semestre 10 */
  { id:'OBMA_J001', nombre:'Internado Intrahospitalario', cod:'OBMA J001', sem:10,
    req:['OBMA_G002','OBMA_H002'] },
  { id:'ELECOBMA01', nombre:'Electivo I (Décimo)', cod:'ELECOBMA01', sem:10, req:[] },
  { id:'ELECOBMA02', nombre:'Electivo II (Décimo)', cod:'ELECOBMA02', sem:10, req:[] },
];

/* === Estado in‑memory =========================================== */
const estado = {};  // { id: { approved: boolean, element: HTMLElement } }

/* === Render inicial ============================================= */
const grid = document.getElementById('grid');
let semestreActual = 0;

cursos.forEach(c => {
  /* Inserta título de semestre cuando cambia */
  if (c.sem !== semestreActual) {
    semestreActual = c.sem;
    const h = document.createElement('div');
    h.className = 'semester';
    h.textContent = `Semestre ${semestreActual}`;
    grid.appendChild(h);
  }

  /* Caja de curso */
  const div = document.createElement('div');
  div.className = 'course';
  div.innerHTML = `
      <span class="nombre">${c.nombre}</span>
      <span class="code">${c.cod}</span>
      <span class="tick">✓</span>
  `;
  grid.appendChild(div);

  estado[c.id] = { approved:false, element:div, req:c.req };

  /* Marca como disabled si tiene requisitos */
  if (c.req.length) div.classList.add('disabled');

  div.addEventListener('click', () => toggleCurso(c.id));
});

/* === Función de toggle ========================================== */
function toggleCurso(id) {
  const curso = estado[id];
  if (curso.element.classList.contains('disabled')) return; // bloqueado

  curso.approved = !curso.approved;
  curso.element.classList.toggle('approved', curso.approved);

  // Cada vez que cambia algo, recalcula qué ramos se desbloquean
  recalcularBloqueos();
}

/* --- Desbloquea / bloquea según requisitos cumplidos ------------- */
function recalcularBloqueos() {
  Object.entries(estado).forEach(([id, info]) => {
    if (info.approved) return; // ya aprobado, queda clickable

    const cumplidos = info.req.every(r => estado[r]?.approved);
    info.element.classList.toggle('disabled', !cumplidos);
  });
}

/* === Inicial ===================================================== */
recalcularBloqueos();

function getProfile() {
  return {
    name: 'Bayu Kusuma Wardana ',
    age: 20
    address: 'Jl.Balai Desa Jabon Mekar, Kec.Parung Kab.Bogor Jawa Barat',
    hobbies: ['Bermain Gitar'] //Array,
    is_married: false //Boolean,
    school: {
      elementary school: 'SDN TANAH TINGGI 03', < year_in="2005" > , < year_out="2010" >
      Junior High School: 'SMPN 7 KOTA TANGERANG' , < year_in="2011" > , < year_out="2013"
      highSchool: 'SMAN 1 Tajurhalang', < year_in="2014" > , < year_out="2017" >
      university: 'null'
    }, // Array Of Object
    skills: [{
      name: 'adobe lightroom',
      years_of_experience: 1
      level: advanced
    },{
      name: 'software mobile phone',
      years_of_experience: 3
      level: advanced
    }] // Array Of Object
    interest_in_coding: true //Boolean,
  }
}
let profile = getProfile();

let skills = profile.skills;

// megakses sekolah
let highschool = profile.school.highscool;
//atau pakai es6

let {skills} = profile;

// print json yang telah di convert ke type String
console.log(JSON.stringify(skills));

 fungsi dari JSON dari web API tapi pada dasarnya sangat sederhana yaitu sebagai format untuk mentransmisikan (mengirim dan menerima) data dari web API (server) ke client atau sebaliknya.

# actocweb26
import React from 'react';
import { motion } from 'framer-motion';

export default function ACTOCWebsite() {
  return (
    <div className="min-h-screen bg-gradient-to-b from-[#071a2d] via-[#0d2238] to-[#f5efe3] text-white font-sans scroll-smooth">
      <nav className="flex justify-between items-center px-6 md:px-10 py-5 border-b border-white/10 sticky top-0 bg-[#071a2d]/90 backdrop-blur z-50">
        <div className="flex items-center gap-3">
          <div className="w-12 h-12 rounded-full bg-white/10 flex items-center justify-center text-xs">LOGO</div>
          <div>
            <div className="text-2xl font-black tracking-wide">ACTOC</div>
            <div className="text-[10px] text-white/60 leading-tight">Advancing Children in Technology Orange County</div>
          </div>
        </div>
        <div className="hidden md:flex gap-8 text-sm items-center">
          <a href="#about" className="hover:text-[#e7c07d] transition">About</a>
          <a href="#programs" className="hover:text-[#e7c07d] transition">Programs</a>
          <a href="#impact" className="hover:text-[#e7c07d] transition">Impact</a>
          <a href="#founders" className="hover:text-[#e7c07d] transition">Founders</a>
          <a href="#partner" className="hover:text-[#e7c07d] transition">Partner</a>
          <button className="bg-[#e7c07d] text-black px-5 py-2 rounded-2xl font-semibold hover:scale-105 transition">Get Involved</button>
        </div>
      </nav>

      <section className="grid md:grid-cols-2 gap-10 px-6 md:px-10 py-20 md:py-24 items-center">
        <motion.div initial={{opacity:0,y:30}} animate={{opacity:1,y:0}} transition={{duration:0.8}}>
          <h1 className="text-4xl md:text-6xl font-black leading-tight mb-6">Every child deserves <span className="text-[#e7c07d]">STEM</span>, <span className="text-[#8fc7d6]">robotics</span>, and <span className="text-[#c96a5a]">wellness</span> for free.</h1>
          <p className="text-lg text-white/70 mb-8 max-w-xl">Two high school students built ACTOC because too many children never get access to the opportunities that shape confidence, health, and future careers.</p>
          <div className="flex flex-wrap gap-4 mb-10">
            <a href="#programs" className="bg-white text-black px-6 py-3 rounded-2xl font-semibold shadow-2xl hover:scale-105 transition">See Our Programs</a>
            <a href="#partner" className="border border-white/20 px-6 py-3 rounded-2xl hover:bg-white/10 transition">Partner With Us</a>
          </div>
          <div className="grid grid-cols-3 gap-4 max-w-md">
            <div><div className="text-3xl font-bold text-[#e7c07d]">$0</div><div className="text-white/60">Cost to families</div></div>
            <div><div className="text-3xl font-bold text-[#8fc7d6]">2</div><div className="text-white/60">Programs</div></div>
            <div><div className="text-3xl font-bold text-[#c96a5a]">∞</div><div className="text-white/60">Potential</div></div>
          </div>
        </motion.div>
        <div className="bg-white/5 rounded-[2rem] h-[380px] md:h-[450px] flex items-center justify-center text-white/30 text-xl border border-white/10 shadow-2xl hover:scale-[1.02] transition">Insert ACTOC Logo PNG</div>
      </section>

      <section id="about" className="px-6 md:px-10 py-20 md:py-24 bg-white text-black rounded-t-[3rem]">
        <p className="uppercase text-sm tracking-[0.3em] text-black/40 mb-4">The Problem</p>
        <h2 className="text-3xl md:text-4xl font-black max-w-4xl mb-12">Kids do not miss out for one reason. They miss out because every barrier shows up at once.</h2>
        <div className="grid md:grid-cols-2 gap-8">
          <div className="bg-[#d9edf2] p-8 rounded-3xl shadow-xl hover:-translate-y-2 transition"><h3 className="text-2xl font-bold mb-4">The STEM Access Gap</h3><ul className="space-y-3 text-black/70"><li>School budgets cannot sustain STEM programs</li><li>Families cannot afford robotics fees and materials</li><li>Limited nearby enrichment opportunities</li><li>No early exposure to innovation pathways</li></ul></div>
          <div className="bg-[#f4ddd6] p-8 rounded-3xl shadow-xl hover:-translate-y-2 transition"><h3 className="text-2xl font-bold mb-4">The Wellness Education Gap</h3><ul className="space-y-3 text-black/70"><li>Nutrition and mental health are deprioritized</li><li>Body literacy is rarely taught accessibly</li><li>Schools lose wellness curriculum first</li><li>Families lack child-friendly resources</li></ul></div>
        </div>
      </section>

      <section id="programs" className="px-6 md:px-10 py-20 md:py-24 text-black bg-white">
        <h2 className="text-4xl md:text-5xl font-black mb-12">Two Programs. One Mission.</h2>
        <div className="grid md:grid-cols-2 gap-8">
          <div className="bg-gradient-to-br from-[#d9edf2] to-[#eef8fb] p-8 rounded-3xl shadow-xl hover:-translate-y-2 transition"><h3 className="text-3xl font-bold mb-4">ACTOC Robotics</h3><p className="mb-4">Free hands-on STEM and robotics workshops for elementary students designed to build curiosity, confidence, and early engineering exposure.</p><p>No materials cost. No school budget required. We bring everything.</p></div>
          <div className="bg-gradient-to-br from-[#f4ddd6] to-[#f5efe3] p-8 rounded-3xl shadow-xl hover:-translate-y-2 transition"><h3 className="text-3xl font-bold mb-4">ACTOC Wellness Series</h3><p className="mb-4">A three-book children's wellness series covering Nutrition, Body Health, and Mental Health paired with free school and library presentations.</p><p>Future book proceeds will support schools in poverty areas globally.</p></div>
        </div>
      </section>

      <section id="impact" className="px-6 md:px-10 py-20 md:py-24 bg-[#071a2d] text-white">
        <h2 className="text-4xl font-black mb-12">Our 2026 Goals</h2>
        <div className="grid md:grid-cols-5 gap-6">
          {['Launch Workshops','Publish 3 Wellness Books','Start Chapters','International Outreach','Increase Volunteers'].map((goal)=>(<div key={goal} className="bg-white/5 rounded-3xl p-6 border border-white/10 hover:bg-white/10 transition">{goal}</div>))}
        </div>
      </section>

      <section id="founders" className="px-6 md:px-10 py-20 bg-[#f5efe3] text-black">
        <h2 className="text-4xl font-black mb-10 text-center">Built by students. For every student.</h2>
        <div className="grid md:grid-cols-2 gap-8">
          <div className="bg-white p-8 rounded-3xl shadow-xl hover:-translate-y-2 transition"><h3 className="text-2xl font-bold">Nitika Metharamitta</h3><p className="text-[#c96a5a] mb-4">Co-Founder & President</p><p>Passionate about creating equal access to STEM education and helping students discover innovation pathways early.</p></div>
          <div className="bg-white p-8 rounded-3xl shadow-xl hover:-translate-y-2 transition"><h3 className="text-2xl font-bold">Amulya Atluri</h3><p className="text-[#c96a5a] mb-4">Co-Founder & Vice President</p><p>Dedicated to child wellness education and ensuring young students grow with stronger health literacy and confidence.</p></div>
        </div>
      </section>

      <section id="partner" className="px-6 md:px-10 py-20 bg-[#e7c07d] text-black text-center">
        <h2 className="text-4xl md:text-5xl font-black mb-6">Help us build access that actually reaches every child.</h2>
        <p className="max-w-2xl mx-auto mb-8 text-black/70">Partner, volunteer, donate materials, or host ACTOC at your school, library, or organization.</p>
        <div className="flex flex-wrap justify-center gap-4">
          <button className="bg-black text-white px-6 py-3 rounded-2xl hover:scale-105 transition">Become a Partner</button>
          <button className="border border-black px-6 py-3 rounded-2xl hover:bg-black/5 transition">Volunteer</button>
          <button className="border border-black px-6 py-3 rounded-2xl hover:bg-black/5 transition">Donate</button>
        </div>
        <div className="mt-12 max-w-xl mx-auto bg-white/40 rounded-3xl p-8">
          <h3 className="text-2xl font-bold mb-4">Contact ACTOC</h3>
          <input className="w-full p-3 rounded-xl mb-3" placeholder="Name" />
          <input className="w-full p-3 rounded-xl mb-3" placeholder="Email" />
          <textarea className="w-full p-3 rounded-xl mb-3" placeholder="Message" rows="4"></textarea>
          <button className="bg-black text-white px-6 py-3 rounded-2xl">Send Message</button>
        </div>
      </section>

      <footer className="px-6 md:px-10 py-10 bg-[#071a2d] text-white/70 text-center">
        <p>ACTOC • Advancing Children in Technology Orange County</p>
        <p className="mt-2 text-sm">Student-led 501(c)(3) nonprofit organization • 2026</p>
        <p className="mt-2 text-sm">info@actoc.org • Orange County, California</p>
      </footer>
    </div>
  );
}

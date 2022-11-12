<script lang="ts">
  import { Icon } from "@steeze-ui/svelte-icon";
  import { MapPin, Clock, Phone, ChevronRight, Beaker, ShieldCheck, Banknotes, ExclamationCircle, AtSymbol } from "@steeze-ui/heroicons";
  import { Twitter, Facebook, Linkedin, Instagram } from "@steeze-ui/remix-icons";
</script>

<div class="w-full flex flex-col justify-center items-center sm:gap-y-10 gap-y-3">
  <div class="flex justify-center items-center bg-slate-700 p-5 sm:mt-10 mt-3 rounded-2xl gap-x-10 w-11/12 sm:w-max">
    <img src="logo.png" class="sm:w-36 w-40" alt="logo" />
    <div class="justify-center items-center gap-x-5 hidden sm:flex">
      <div class="w-0.5 bg-slate-600 h-10" />
      <a href="/#home" class="px-2 py-1 rounded-lg text-white border-sky-500 hover:border-b-2 transition-all duration-75 font-bold cursor-pointer">Home</a>
      <div class="w-0.5 bg-slate-600 h-10" />
      <a href="/#about" class="px-2 py-1 rounded-lg text-white border-sky-500 hover:border-b-2 transition-all duration-75 font-bold cursor-pointer">About</a>
      <div class="w-0.5 bg-slate-600 h-10" />
      <a href="/#service" class="px-2 py-1 rounded-lg text-white border-sky-500 hover:border-b-2 transition-all duration-75 font-bold cursor-pointer">Service</a>
    </div>
  </div>
  <div class="h-0.5 w-1/2 bg-slate-600" />
  <div class="flex flex-col sm:flex-row justify-center items-center gap-x-10 gap-y-3 scroll-my-20" id="home">
    <div class="sm:w-[30rem] sm:h-[30rem] w-72 flex justify-center items-center">
      <div class="border-2 border-lime-500 rounded-3xl sm:p-10 p-5">
        <p class="font-bold sm:text-4xl text-4xl text-center text-white sm:mb-5 mb-2">Welcome to Tatbills</p>
        <p class="text-2xl text-slate-200 text-center font-bold">Where Your Financial Health is Our <span class="underline text-sky-400">Top</span> Priority</p>
      </div>
    </div>
    <div class="border-2 border-sky-500 overflow-hidden rounded-3xl h-max">
      <img src="home.jpg" alt="home" class="sm:w-[30rem] sm:h-[30rem] w-72 h-72 object-cover" />
    </div>
  </div>
  <div class="flex flex-col sm:flex-row-reverse justify-center items-center gap-x-10 gap-y-3 scroll-my-20" id="about">
    <div class="sm:w-[30rem] sm:h-[30rem] w-72 flex justify-center items-center overflow-hidden rounded-3xl">
      <div class="rounded-3xl sm:p-10 p-5 border-2 border-lime-500 overflow-auto max-h-[480px] scrollbar">
        <p class="font-bold sm:text-4xl text-4xl text-center sm:text-left text-white sm:mb-5 mb-2">About Us!</p>
        <p class="text-xl text-slate-400 text-left ">
          Tatbills is a national U.S. based privately owned and operated Physician Billing Service Group based in Atlanta, Georgia. With years of combined leadership in healthcare, our management and billing team works closely with each client. Increase cash flow and compliancy through continuous
          education sets our organization apart from other billing companies. Unlike no other medical billing company, we offer flexible continuous analytical technique to help you reach your maximizing efficiency, so we can timely file your reimbursement claims. We realized the ever-changing
          complex hurdles to the healthcare landscapes creates much uncertainty for many medical practices and health care organizations. At Tatbills, we tailor our medical billing services based on your organizational needs. Clients have open access to our billing team so claims are timely
          processed and you get paid for medical services rendered. Many physicians’ practices, personal injury attorneys, worker’s compensation networks and hospitalists throughout the United States make it a point to depend on us. Our goal is to increase your overall financial health, audit and
          educate our healthcare partners so to optimize payment of medical services performed and rendered. Coding compliantly through communication and education surpasses all other medical billing companies. Let us show you how we can complement your medical practice and help you increase cash
          flow and efficiency. As an extension to physician practices the role of a qualified medical billing and coder can be the lifeline to a medical practice. Medical billing codes tell the story of a patient’s encounter with a medical provider and summarize a treatment plan. If physicians do
          not properly code a face-toface encounter with a patient, this slight error can cost a medical practice thousands of dollars each month. Loss of revenue can be detrimental to a thriving medical practice and could also restrict a patient from qualifying from ancillary services they may need
          and qualify for. Tatbills offers a comprehensive solution helping medical practices optimize their financial health with complete transparency. We offered tailored support options allowing clients to select the level of involvement as a healthcare partner. Often physicians are bogged down
          with the daily
        </p>
      </div>
    </div>
    <div class="border-2 border-sky-500 overflow-hidden rounded-3xl">
      <img src="about.jpg" alt="about" class="sm:w-[30rem] sm:h-[30rem] w-72 h-72 object-cover" />
    </div>
  </div>
  <div class="h-0.5 w-1/2 bg-slate-600" />
  <div class="border-2 border-sky-500 text bg-slate-700 text-white font-bold p-5 text-3xl rounded-xl" id="service">WHY CHOOSE US?</div>
  <div class="flex flex-wrap justify-center items-center w-full gap-x-5 gap-y-3 sm:gap-y-5">
    <div class="bg-slate-700 p-5 rounded-xl flex flex-col justify-center items-center gap-y-2 sm:max-w-sm max-w-xs">
      <div class="bg-slate-800 rounded-lg p-2 w-max flex justify-center items-center gap-x-3">
        <Icon src={ExclamationCircle} theme="solid" class="text-sky-500 w-10 h-10" />
        <p class="text-white font-bold text-xl">Claim Denials</p>
      </div>
      <p class="text-slate-300 text-xl text-left max-h-80 overflow-y-scroll scrollbar">
        A number of medical practices submit reimbursement claims and for whatever reason their medical claims are denied. Stacks of denials pile up in the office. Often times physicians are unaware of the denials as most physicians entrust their financial health to the practice manager. Medical
        offices get busy and working denied medical claims often does not become a priority. Nothing is done with that encounter to correct any issues that the insurance company is claiming is preventing you from receiving payment from the insurance company. At Tatbills we want to make sure that
        every claim that is submitted on your behalf is paid.
      </p>
    </div>
    <div class="bg-slate-700 p-5 rounded-xl flex flex-col justify-center items-center gap-y-2 sm:max-w-sm max-w-xs">
      <div class="bg-slate-800 rounded-lg p-2 w-max flex justify-center items-center gap-x-3">
        <Icon src={ShieldCheck} theme="solid" class="text-sky-500 w-10 h-10" />
        <p class="text-white font-bold text-xl">Protect Your Revenue</p>
      </div>
      <p class="text-slate-300 text-xl text-left max-h-80 overflow-y-scroll scrollbar">
        During multiple audits done by Tatbills, we have found that some physician practices generally do nothing with a denied claim and end up “writing off” rejected medical claims. Administrative write-offs involving a non paid claim does nothing for financial health of any medical practice.
        Write off claims are just indicators that a medical practice has room for systematic financial improvement and could benefit from revenue cycle management support. At Tatbills, we specialize in developing a comprehensive action plan correcting the claim denial management processes with a
        solid prevention-focused strategy. With Tatbills, our experienced team makes sure that medical claims are timely filed to increase physician practice’s cash flow. The never ending mandated updates to the ICD-10-CM and classification systems can be difficult at times to interpret while
        physicians are maintaining a busy medical practice. Often times insurance claims are not only complex, but unclear on how to interpret. Coding compliancy through education creates internal checks and balances as your medical billing partner. With the ever-changing rules in medical billing,
        our expertise will be a great resource to relieving the headaches in your daily battle against the constantly updating process of billing. We offer assistance with billing, coding, and other common issues associated with medical billing. Allow our team to put your business on the path to
        forgetting these stresses. We are passionate about doing our best to let physicians do what they went to medical school for years for instead of trying to grapple with an area far out of their own expertise. A fundamental aspect of finance is a dollar today is worth more than a dollar
        tomorrow, and with us we will make sure that dollar is given back to you at the earliest possible day so you can utilize it in the way you see best. Insurance companies want to hold onto that money for as long as possible and make your claim as difficult as they can, oftentimes they can feel
        like an opponent instead of just a third party you do business with
      </p>
    </div>
    <div class="bg-slate-700 p-5 rounded-xl flex flex-col justify-center items-center gap-y-2 sm:max-w-sm max-w-xs">
      <div class="bg-slate-800 rounded-lg p-2 w-max flex justify-center items-center gap-x-3">
        <Icon src={Banknotes} theme="solid" class="text-sky-500 w-10 h-10" />
        <p class="text-white font-bold text-xl">Accelerate Cash Flow</p>
      </div>
      <p class="text-slate-300 text-xl text-left max-h-80 overflow-y-scroll scrollbar">
        In order to reduce medical denial claims, it is important for medical practices to proactively work towards developing internal systems required to decrease the likelihood of a claim denial. First, it is important for medical practices to gain a better understanding as to the most common
        reasons why a medical claim would be denied. Understanding the most common reasons for a denial and developing internal safeguards and protocols within the billing process can help identify foreseen problems prior to medical services rendered. At Tatbills, we offer a comprehensive approach
        to EDUCATE. COMMUNICATE. DELIVER.services for physicians of all specialties. Whether you are a single group provider or in a large physician group, we offer either one-on-one training with practice physicians and staff or for the entire group to be more efficient in their day to day
        administrative tasks. Our audits are offered in hourly increments. Through detailed chart audits and due diligence, our team members can help you identify areas of opportunities and make recommendations for improvements to coding, documentation and process improvement.
      </p>
    </div>
  </div>
  <div class="bg-slate-700 w-full p-5 flex flex-col justify-center items-center">
    <div class="flex flex-col sm:flex-row justify-around items-start w-full h-full gap-x-10 gap-y-5">
      <div class="flex flex-col justify-center items-start gap-y-2">
        <p class="text-2xl text-white mb-3">Info</p>
        <div class="flex justify-center items-center gap-x-2 bg-slate-600 rounded-lg py-1 px-2 shadow-sm">
          <Icon src={MapPin} theme="solid" class="text-sky-400 w-7 h-7" />
          <p class="text-slate-200">Georgia USA</p>
        </div>
        <div class="flex justify-center items-center gap-x-2 bg-slate-600 rounded-lg py-1 px-2 shadow-sm">
          <Icon src={Clock} theme="solid" class="text-sky-400 w-7 h-7" />
          <p class="text-slate-200">Mon - Sat 08:00 AM - 08:00 PM EST</p>
        </div>
        <div class="flex justify-center items-center gap-x-2 bg-slate-600 rounded-lg py-1 px-2 shadow-sm">
          <Icon src={Phone} theme="solid" class="text-sky-400 w-7 h-7" />
          <p class="text-slate-200">+1 3522813949</p>
        </div>
        <div class="flex justify-center items-center gap-x-2 bg-slate-600 rounded-lg py-1 px-2 shadow-sm">
          <Icon src={AtSymbol} theme="solid" class="text-sky-400 w-7 h-7" />
          <a href="mailto:btat@tatbills.com" class="text-slate-200 underline">btat@tatbills.com</a>
        </div>
        <div class="flex justify-center items-center gap-x-3">
          <div class="bg-slate-600 p-1 rounded-lg shadow-sm">
            <Icon src={Twitter} theme="solid" class="text-sky-400 w-7 h-7" />
          </div>
          <div class="bg-slate-600 p-1 rounded-lg shadow-sm">
            <Icon src={Facebook} theme="solid" class="text-sky-400 w-7 h-7" />
          </div>
          <div class="bg-slate-600 p-1 rounded-lg shadow-sm">
            <Icon src={Linkedin} theme="solid" class="text-sky-400 w-7 h-7" />
          </div>
          <div class="bg-slate-600 p-1 rounded-lg shadow-sm">
            <Icon src={Instagram} theme="solid" class="text-sky-400 w-7 h-7" />
          </div>
        </div>
      </div>
      <div class="flex flex-col justify-center items-start gap-y-2">
        <p class="text-2xl text-white mb-3">Quick links</p>
        <div class="flex justify-center items-center gap-x-2 cursor-pointer">
          <Icon src={ChevronRight} theme="solid" class="text-white w-5 h-5" />
          <a href="/#home" class="text-slate-200">Home</a>
        </div>
        <div class="flex justify-center items-center gap-x-2 cursor-pointer">
          <Icon src={ChevronRight} theme="solid" class="text-white w-5 h-5" />
          <a href="/#about" class="text-slate-200">About</a>
        </div>
        <div class="flex justify-center items-center gap-x-2 cursor-pointer">
          <Icon src={ChevronRight} theme="solid" class="text-white w-5 h-5" />
          <a href="/#service" class="text-slate-200">Service</a>
        </div>
      </div>
    </div>
    <a href="mailto:matin.tat85@gmail.com" class="text-slate-400 text-center">Designed by Matin Tat</a>
  </div>
</div>

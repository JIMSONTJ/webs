# webs
import react from "react";
import Image from "next/image";

const Firs = () =>{
    return(
        <div>
            <div className="flex flex-row gap-40">
            <div className="mt-32 ml-10 ">
            <Image
            src="/media/mic.png"
            alt=""
            width="300"
            height="250"
            />
            </div>
            <div>
            <Image
            src="/media/mon.png"
            alt=""
            width="300"
            height="250"
            />
            </div>
            <div className="mt-32">
            
            <Image
            src="/media/men.png"
            alt=""
            width="290"
            height="250"
            />
            </div>
            </div>

            <div className="text-[#ffffff] flex align-middle justify-center items-center flex-col "> 
            <div className="flex flex-col mr-3">
            <div className="flex  ">
<div className="text-[#fcbec6] text-4xl font-sans">Web3 </div><div className="text-[#fcbec6] text-4xl font-sans">#REHASHED</div></div>
<div className=" mt-6 font-extralight">V E R B</div>

<div className="mt-4">past tense: rehashed; past participle: rehashed</div>

<div className="mt-2">/riːˈhaʃ/</div>

<div className="text-xl mt-10 ">A pocket-sized recap of an overwhelming 2022 written with <br/>the intention to pay an ode to a stellar #CryptoCommunity.</div>
</div>
</div>

            <div className="flex flex-row gap-40">
            <div className="-mt-40 ml-4">
            <Image
            src="/media/ho.png"
            alt=""
            width="320"
            height="250"
            /></div>
            <div className="mt-20">
            <Image
            src="/media/hea.png"
            alt=""
            width="350"
            height="250"
            /></div>
            <div className="-mt-52 ">
            <Image className="rounded-xl"
            src="/media/ki.png"
            alt=""
            width="400"
            height="50"
            /></div>
            </div>

     
        </div>



    )







}
export default Firs;

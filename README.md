import logo from "../../assets/logo.svg";
import { TbPointFilled } from "react-icons/tb";
import "./Desafios.css";

export default function () {
    return (
        <div className="Desafios">
            <div className="desafiosSection">
                <img
                    className="logo-desafios"
                    width={100}
                    src={logo}
                    alt="StreamEats Cherry Logo"
                />
                <h1 className="c-primary"><span className="f-weight-bold">Desafios existentes na interação com o público</span></h1>
                <div className="point-and-text">
                    <TbPointFilled /><p className="primeiro">Engajamento e participação do público</p>
                </div>
                <div className="point-and-text">
                    <TbPointFilled /><p className="primeiro">Falta de experiências reais e tangíveis com o público</p>
                </div>
                <div className="point-and-text">
                    <TbPointFilled /><p className="primeiro">Criar ligação forte com o público</p>
                </div>
            </div>
            
        </div>
    );
}


.Desafios{
    min-height: 100vh;
    width: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
}

.desafiosSection{
    display: flex;
    flex-direction: column;
    align-items : center;
    gap: 15px;
    padding-top: 25%;
}

.c-primary{
    text-align: center; 
    padding-bottom: 25px;
    font-size: 40PX;
}
.point-and-text {
    display: flex;
    align-items: center;
    gap: 10px;
    color: #6a6a74;
    width: 100%; 
    padding-left: 10%;
    font-family: 'Roboto', sans-serif;
    padding-bottom: 12px;
    font-size: 30px;
    
}

.c-primary{
    padding-top: 45px;
}
.Desafios{
    min-height: 100vh;
    width: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
}

.desafiosSection{
    display: flex;
    flex-direction: column;
    align-items : center;
    gap: 15px;
    padding-top: 25%;
}

.c-primary{
    text-align: center; 
    padding-bottom: 25px;
    font-size: 40PX;
}
.point-and-text {
    display: flex;
    align-items: center;
    gap: 10px;
    color: #6a6a74;
    width: 100%; 
    padding-left: 10%;
    font-family: 'Roboto', sans-serif;
    padding-bottom: 12px;
    font-size: 30px;
    
}

.c-primary{
    padding-top: 45px;
}







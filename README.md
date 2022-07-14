# goit-markup-hw-05
animation

position: absolute;
top: 0;
right: 0;
bottom: 0;
left: 0;
background-image: linear-gradient(180deg, transparent 0, var(--overlay-color) );
width: 370px;



  /*Modal*/
        .backdrop{
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color:rgba(0, 0, 0, 0.2);
            z-index: 20;
        
        }

        .modal{
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 528px;
            min-height: 581px;
            background-color: rgba(255, 255, 255, 1);
            box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 0px 1px 1px rgba(0, 0, 0, 0.14), 0px 2px 1px rgba(0, 0, 0, 0.2);
            border-radius: 4px;
            
        }

        .modal-close-button{
           position: absolute;
           top: 8px;
           right: 8px;
           width: 30px;
           height: 30px; 
        }
        





# ajuda
Não to conseguindo mudar o tamanho e a posiçao dos objetos

import javax.swing.JFrame;
import javax.swing.JRadioButton;
import java.awt.Component;
import javax.swing.JButton;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;
import java.awt.GridLayout;
public class Casa extends JFrame {
	public static void main(String[] args) {
	
		
		JFrame casa = new JFrame ("A casa");
      JButton jbQuarto1 = new JButton("Quarto 1 ");
      jbQuarto1.addActionListener(new ActionListener(){
    	  public void actionPerformed(ActionEvent arg1) {
    	  
    	  }
      });
     
      casa.add(jbQuarto1);
      casa.setBounds(300,200,400,100);
      casa.setVisible(true);
      
      
      JButton jbQuarto2 = new JButton(" Quarto 2 ");
      jbQuarto1.addActionListener(new ActionListener() {
    	  public void actionPerformed(ActionEvent arg1) {
    	
    	  }   
    	  });
     
      casa.add(jbQuarto2);
      casa.setVisible(true);
      casa.setBounds(1000,3000,400,100);
      
      JButton banheiro = new JButton(" Banheiro ");
      banheiro.addActionListener(new ActionListener() {
      public void actionPerformed(ActionEvent arg1){
      
      }
	
	});
	
      casa.add(banheiro);
  
	casa.setVisible(true);
	
	
			JButton banheiro2 = new JButton(" Banheiro 2 ");
			banheiro2.addActionListener(new ActionListener() {
				public void actionPerformed(ActionEvent arg1 ) {
					
				}
			});
         
			casa.add(banheiro2);
         
          
          casa.setVisible(true);
	
	   JButton mostrar = new JButton("Mostrar");
	   mostrar.addActionListener(new ActionListener() {
	   public void actionPerformed(ActionEvent arg1) {
	}
	});
	
	   casa.add(mostrar);
    casa.setBounds(200,400,400,100);
	   casa.setLocationRelativeTo(null);
	casa.setSize(400,500);
	casa.setVisible(true);
	
	}
}
